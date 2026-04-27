pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo '체크체킃케츠케츠케ㅡ..'
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
