pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                bat 'pwsh --version'
            }
        }
        stage('hello friend'){
            steps {
                bat 'python hellofriend.py'
            }
        }
    }
}