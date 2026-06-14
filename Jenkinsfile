pipeline {
    agent any

    stages {

        stage('clone') {
            steps {
                git 'https://github.com/sowjanya-it/Calculator.git'
            }
        }

        stage('compile') {
            steps {
                bat 'javac Calculator.java'
            }
        }

        stage('build') {
            steps {
                bat 'java Calculator'
            }
        }

        stage('test') {
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
