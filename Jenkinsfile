pipeline {
    agent {
        docker {
            image 'python:3.12-alpine' // Updated to use a valid image
        }
    }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
