pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/kushal0234/nodejsApis.git'
            }
        }

        stage('Build') {
            steps {
                // Example build step
                sh 'echo "Building project..."'
            }
        }

        stage('Test') {
            steps {
                // Example test step
                sh 'echo "Running tests..."'
            }
        }

        stage('Deploy') {
            steps {
                // Example deploy step
                sh 'echo "Deploying project..."'
            }
        }
    }
}
