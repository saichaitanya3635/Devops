pipeline {
    agent { label 'test-agent' }  // ✅ Correct syntax
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                script {
                    echo "Workspace Directory: ${env.WORKSPACE}"
                }
            }
        }
    }
}
