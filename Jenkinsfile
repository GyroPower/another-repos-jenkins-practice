pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                bat 'python --version'
            }
        }
        stage('hello friend'){
            steps {
                bat 'python hellofriend.py'
                bat 'docker --version'
                bat 'docker ps'
            }
        }
    }
}