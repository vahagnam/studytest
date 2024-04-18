pipeline {
    agent none
    stages {
        stage('BuildAndTest') {
            agent any
            stages {
                stage('build') {
                    steps {
                        echo "Building stage for build #${env.BUILD_NUMBER}"
                    }
                }
                stage('Test') {
                    steps {
                        echo 'Do Test'
                    }
                }
            }
        }
    }
}
