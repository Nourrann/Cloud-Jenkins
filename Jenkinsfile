pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // Checkout your source code from Git
                git 'https://github.com/Nourrann/Cloud-Jenkins'
            }
        }

        stage('Build') {
            steps {
                // Replace 'sh' with 'bat' for Windows
                bat 'dir'  // Example command, replace with your actual commands
            }
        }

        stage('Test') {
            steps {
                // Replace 'sh' with 'bat' for Windows
                bat 'echo Testing...'  // Example command, replace with your actual commands
            }
        }

        stage('Deploy') {
            steps {
                // Replace 'sh' with 'bat' for Windows
                bat 'echo Deploying...'  // Example command, replace with your actual commands
            }
        }
    }
}
