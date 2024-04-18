pipeline {
    agent none
    stages {
        stage('BuildAndTest') {
            agent any
            stages {
                stage('build') {
                    steps {
                        echo 'Hello world'
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
