pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Fetching DRERMS source code from GitHub...'
            }
        }
        stage('Build & Test') {
            steps {
                echo 'Running automated tests for Disaster Relief System...'
            }
        }
        stage('Docker Deploy') {
            steps {
                echo 'Deploying disaster-relief-app to production on port 3000...'
            }
        }
    }
}
