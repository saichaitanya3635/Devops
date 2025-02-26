pipeline {
    agent { label 'test-agent' }
    stages {
        stage('Clean Workspace') {
            steps {
                cleanWs()
            }
        }
        stage('Build') {
            steps {
                echo "Workspace Directory: ${env.WORKSPACE}"
            }
        }
    }
}
