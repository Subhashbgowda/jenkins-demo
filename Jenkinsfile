pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning the GitHub repo...'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the app...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying to production...'
            }
        }
    }
}
