pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Akash8356/GitHub-CI-CD-Learning.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the app...'
                // Add your build commands here
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add your test commands here
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying app...'
                // Add deploy script/command here
            }
        }
    }
}
