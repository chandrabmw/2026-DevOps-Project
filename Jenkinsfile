
pipeline {
    agent any

    options {
        skipDefaultCheckout()
    }

    stages {
        stage('Checkout') {
            steps {
                checkout scm
                echo 'Code downloaded successfully'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage'
                sh 'ls -la'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing stage placeholder'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment stage placeholder'
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully'
        }

        failure {
            echo 'Pipeline failed'
        }
    }
}
