pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                sh 'python --version'
            }
        }
        stage('hello friend'){
            steps {
                sh 'python hellofriend.py'
            }
        }
    }
}