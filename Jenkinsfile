pipeline {
    agent any
    
    stages {
        stage('Version') {
            steps {
                sh 'python --version'
                sh 'whoami'
            }
        }
        stage('Script execution') {
            steps {
                sh 'python hello.py'
            }
        }
     
    }
    
}
