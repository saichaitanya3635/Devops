pipeline {
    agent any
    stages {
        stage('Check Git Path') {
            steps {
                bat 'where git'  // Should return C:\Program Files\Git\cmd\git.exe
                bat 'git --version'
            }
        }
    }
}
