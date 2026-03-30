pipeline {
    agent any

    stages {
        stage('Stage One') {
            steps {
                sh 'bash scripts/hello_stage1.sh'
            }
        }

        stage('Stage Two') {
            steps {
                sh 'bash scripts/hello_stage2.sh'
            }
        }
    }
}
