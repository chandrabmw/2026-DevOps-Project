
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building application'
                sh 'ls -la'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing application'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application'
            }
        }
    }

    post {
        success {
            echo 'Automation successful'
        }
        failure {
            echo 'Automation failed'
        }
    }
}
