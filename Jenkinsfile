pipeline {
    agent any
    environment {
        PYTHON_HOME = "C:\\Users\\kanch\\AppData\\Local\\Programs\\Python\\Python313"
        PATH = "${PYTHON_HOME};${env.PATH}"
    }
    stages {
        stage('Check Python') {
            steps {
                bat 'python --version'
            }
        }
        stage('Execute Python') {
            steps {
                bat 'python hello.py'
            }
        }
    }
}
