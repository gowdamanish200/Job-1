pipeline {
    agent any  // Use any available agent

    stages {
        stage('Checkout') {
            steps {
                // Check out the code from a Git repository
                git branch: 'main', url: 'https://github.com/your-repo/your-project.git'
            }
        }

        stage('Build') {
            steps {
                // Run a build command (replace with your actual build command)
                sh 'echo "Building the project..."'
            }
        }

        stage('Test') {
            steps {
                // Run tests (replace with your actual test command)
                sh 'echo "Running tests..."'
            }
        }

        stage('Deploy') {
            steps {
                // Deploy the application (replace with your actual deploy command)
                sh 'echo "Deploying the project..."'
            }
        }
    }

    post {
        always {
            // Clean up or send notifications after the pipeline completes
            echo 'Pipeline completed!'
        }
    }
}
