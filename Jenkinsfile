pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Pull the latest code from your GitHub repo
                git branch: 'main', url: 'git@github.com:mostafaemad10/your-repo.git'
            }
        }

        stage('Build') {
            steps {
                // For now, just print a message
                echo 'Building the project...'
            }
        }

        stage('Test') {
            steps {
                // Example test step
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                // Example deploy step
                echo 'Deploying...'
            }
        }
    }
}
