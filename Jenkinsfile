pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                sh 'pwsh --version'
            }
        }
        stage('hello friend'){
            steps {
                sh 'python hellofriend.py'
            }
        }
    }
}