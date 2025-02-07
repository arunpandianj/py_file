pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    bat 'echo Starting Hello World Pipeline'
                    bat 'python -V'
                }
            }
        }

        stage('Execute Batch Script') {
            steps {
                script {
                    bat 'python hello.py'
                }
            }
        }
    }
}
