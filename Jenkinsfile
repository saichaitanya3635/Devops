pipeline {
    agent { label 'test-agent' }
    stages {
        stage('Clean Workspace') {
            steps {
                cleanWs()
            }
        }
        stage('Checkout Code') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                echo "Workspace Directory: ${env.WORKSPACE}"
            }
        }
    }
}
