pipeline {
    agent none
    stages {
        stage('build') {
            agent any
            steps {
                powershell 'docker --version'
            }
        }
    }
}