pipeline {
    agent none
    stages {
        stage('BuildAndTest') {
            agent any
            stages {
                stage('build') {
                    steps {
                        sh 'echo "Hello World!"'
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
