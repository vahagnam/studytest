properties([
parameters {
        choice(name: 'PARAMETER_01', choices: ['ONE', 'TWO'], description: 'Choose an option')
        booleanParam(name: 'BOOLEAN', defaultValue: true, description: 'Enable this option')
        text(name: 'MULTI-LINE-STRING', defaultValue: 'this is a multi-line string parameter example', description: 'Enter some text')
        string(name: 'STRING-PARAMETER', defaultValue: 'scriptcrunch', description: 'Enter a string', trim: true)
    }
])
pipeline {
    agent any
    
    stages {
        stage('Use Parameters') {
            steps {
                echo "Parameter 01: ${params.PARAMETER_01}"
                echo "Boolean: ${params.BOOLEAN}"
                echo "Multi-line String: ${params.MULTI-LINE-STRING}"
                echo "String Parameter: ${params.STRING-PARAMETER}"
            }
        }
    }
}
