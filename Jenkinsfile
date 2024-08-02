pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Building the project..."'
                sh 'ls'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Testing the project..."'
                sh 'pwd'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying the project..."'
                sh 'touch deployment.txt'
                sh 'mv deployment.txt deployed.txt'
            }
        }
    }
}
