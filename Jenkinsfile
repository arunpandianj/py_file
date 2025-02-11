pipeline {
    agent { label 'java_agent' }
    stages {
        stage('Check Python') {
            steps {
                sh 'python3 --version'
            }
        }
        stage('Execute Python') {
            steps {
                sh 'python3 hello.py'
            }
        }
    }
}
