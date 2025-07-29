pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo '🔨 Building the application...'
                // Example build command:
                // sh 'npm install' or 'mvn clean install'
            }
        }

        stage('Test') {
            steps {
                echo '🧪 Running tests...'
                // Example test command:
                // sh 'npm test' or 'mvn test'
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Deploying the application...'
                // Example deploy command:
                // sh './deploy.sh' or use Docker/K8s commands
            }
        }
    }

    post {
        success {
            echo '✅ Pipeline completed successfully!'
        }
        failure {
            echo '❌ Pipeline failed. Check logs for errors.'
        }
    }
}
