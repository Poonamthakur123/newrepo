pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/username/repo-name.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Add build commands here
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add test commands here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add deployment steps here
            }
        }
    }
}
