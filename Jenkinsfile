pipeline {
    agent any  // Runs on any available agent

    stages {
        stage('Clone Repository') {
            steps {
                // Make sure the Git URL is correct
                git url:'https://github.com/Bhargavkulla/Jenkins_repo.git', branch: 'main'
            }
        }

        stage('Build') {
            steps {
                // Replace with actual build commands (e.g., mvn, npm, etc.)
                sh 'echo "Building the application..."'
            }
        }

        stage('Test') {
            steps {
                // Replace with actual test commands (e.g., npm test, pytest, etc.)
                sh 'echo "Running tests..."'
            }
        }

        stage('Deploy') {
            steps {
                // Replace with actual deploy commands (e.g., kubectl, docker, etc.)
                sh 'echo "Deploying application..."'
            }
        }
    }
}
