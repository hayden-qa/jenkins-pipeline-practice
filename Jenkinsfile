pipeline {
    agent any

    stages {
        stage('1. 인사하기') {
            steps {
                echo '안녕하세요! Pipeline을 시작합니다.'
                echo '이건 첫 번째 Stage예요.'
            }
        }

        stage('2. 시간 확인') {
            steps {
                sh 'date'
                echo '현재 시간을 출력했습니다.'
            }
        }

        stage('3. 파일 읽기') {
            steps {
                sh 'cat README.md'
                echo 'README.md 파일 내용을 읽었습니다.'
            }
        }

        stage('4. 작업 완료') {
            steps {
                echo '모든 작업을 마쳤습니다!'
                echo '잘 했어요!'
            }
        }
    }

    post {
        success {
            echo '✅ Pipeline 성공적으로 완료!'
        }
        failure {
            echo '❌ Pipeline 실패! 로그를 확인하세요.'
        }
        always {
            echo '📌 빌드가 끝났습니다.'
        }
    }
}
