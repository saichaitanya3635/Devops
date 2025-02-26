pipeline {
    agent 'test-agent'
    stages {
        stage('Check Git Path') {
            steps {
                bat 'where git'  // Should return C:\Program Files\Git\cmd\git.exe
                bat 'git --version'
            }
        }
    }
}
