pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                cleanWs() 
                checkout scm
            }
        }
        stage('Debug & Run') {
            steps {
                sh 'ls -R' 
                sh 'python3 script.py'
            }
        }
    }
}
