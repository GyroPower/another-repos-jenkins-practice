pipeline {
    agent any
    stages {
        stage('build-docker-python-container') {
            steps {
                bat 'docker run --name python-container-test python:3.12.0-alpine3.17'
            }
        }
        stage('hello friend'){
            steps {
                bat 'docker exec python-container-test python3 --version'
                
            }
        }
    }
}