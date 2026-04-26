pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out source code...'
            }
        }
        stage('Install') {
            steps {
                echo 'Installing dependencies...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Build') {
            steps {
                echo 'Building application...'
            }
        }
    }
    post {
        success {
            echo 'Pipeline 성공적으로 완료!'
        }
        failure {
            echo 'Pipeline 실패!'
        }
    }
}
