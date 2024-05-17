pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                sh 'echo "Building..."'
                sh 'ls -l'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Testing..."'
                sh 'npm test'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying..."'
                // Add deployment steps here
            }
        }
    }
}
