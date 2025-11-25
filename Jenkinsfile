pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/your-user/your-repo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the app...'
                // Commands like: npm install
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Commands like: npm test
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Commands for deployment (FTP / Docker / Heroku)
            }
        }
    }
}
