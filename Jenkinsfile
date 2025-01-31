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
        stage ("Deploy") {
            steps {
            echo "Hello World!"
            }
        }
    }
}
