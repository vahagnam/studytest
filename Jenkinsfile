properties([
    parameters([
        choice(choices: ['None', 'AWS', 'Azure'], name: 'CLOUD_PLATFORM', description: 'Select the Cloud Platform'),
        choice(choices: ['dev', 'stag', 'prod'], name: 'environment', description: 'Choose your Environment'),
        choice(choices: ['start', 'stop'], name: 'INFRA_DEPLOYMENT', description: 'The option start will deploy the infra structure and stop will destroy the whole infra structure'),
        string(name: 'Game_ID', defaultValue: 'GID', description: 'Enter the Game ID of the Tournament, Used for Manage workspace', trim: true),
        choice(choices: ['1', '2', '3', '4', '5', '6', '7', '8', '9', '10', '25', '50', '100', '200'], name: 'vm_count', description: 'The no of vms for the vm scaleset default value is 1')
    ])
])
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
