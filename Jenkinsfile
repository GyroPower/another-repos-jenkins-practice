pipeline {
    agent { docker { image 'python:3.11.4-slim-buster' } }
    stages {
        stage('log python version') {
            steps {
                echo 'python version:'
                sh 'python --version'
            }
        }
        
        
    }
}