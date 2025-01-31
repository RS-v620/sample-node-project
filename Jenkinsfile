pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout code from version control
                checkout scm
            }
        }
        stage('Build') {
            steps {
                // Build your project
                bat 'npm install'
            }
        }
        stage('Test') {
            steps {
                // Run tests
                bat 'npm test'
            }
        }
    }
}
