pipeline {
    agent any

    stages {
        stage('Check Docker Version') {
            steps {
                sh 'docker --version'
            }
        }

        stage('List Running Containers') {
            steps {
                sh 'docker ps -a'
            }
        }

        stage('Show Disk Space') {
            steps {
                sh 'df -h'
            }
        }

        stage('Hello from Shell') {
            steps {
                sh '''
                    echo "Hello Subhash!"
                    echo "This is a custom shell script running inside Jenkins"
                '''
            }
        }
    }
}

