pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from the specified branch
                git branch: 'main', url: 'https://github.com/Yuva-aj/jenkins-practice.git'
            }
        }
        stage('Build') {
            steps {
                // Add your build steps here
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                // Add your test steps here
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                // Add your deploy steps here
                echo 'Deploying...'
            }
        }
    }
}
