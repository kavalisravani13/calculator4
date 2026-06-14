pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Source Code Downloaded Successfully'
            }
        }

        stage('Compile') {
            steps {
                bat 'javac Hello.java'
            }
        }

        stage('Execute') {
            steps {
                bat 'java Hello'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Completed'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment Completed'
            }
        }
    }
}
