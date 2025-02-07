pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    bat 'python hello.py'
                }
            }
        }
    }
}
