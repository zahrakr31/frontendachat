pipeline {
    agent any

    environment {
        APP_NAME = "frontendachat"
    }

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/zahrakr31/frontendachat.git'
            }
        }

        stage('Test') {
            steps {
                echo "Running tests"
                sh 'echo "tests passed"'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying..."
                sh 'echo "deploy step here"'
            }
        }
    }
}
