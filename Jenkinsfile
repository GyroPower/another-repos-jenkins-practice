pipeline {
    agent any
    stages {
        stage('build-docker-python-container') {
            steps {
                bat 'docker run --name python-container-test -it -d python:3.12.0-alpine3.17'
            }
        }
        stage('See container works'){
            steps {
                bat 'docker exec python-container-test python3 --version'
                bat 'docker stop python-container-test'
                echo "container python-container-test stops"
            }
        }
        stage('remove container'){
            steps{
                bat 'docker rm python-container-test'
                echo 'container removed'
            }
        }
    }
}