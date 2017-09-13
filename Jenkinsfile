pipeline {
    agent { docker 'python:3.5.1' }
    stages {
      stage('debug') {
            steps {
                bat 'echo hello world'
            }
        }
        stage('build') {
            steps {
                bat 'python --version'
            }
        }
    }
}
