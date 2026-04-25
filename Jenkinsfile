pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo '안녕하세요! Pipeline 시작합니다.'
            }
        }

        stage('Show Date') {
            steps {
                $(date) 'echo 현재 시간: %DATE% %TIME%'
            }
        }

        stage('Read File') {
            steps {
                $(date) 'cat README.md'
            }
        }
    }

    post {
        success {
            echo '✅ Pipeline 성공!'
        }
        failure {
            echo '❌ Pipeline 실패!'
        }
    }
}
