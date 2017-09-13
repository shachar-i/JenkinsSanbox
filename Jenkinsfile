pipeline {
    agent { docker 'python:3.5.1' }
    stages {
      stage('debug') {
            steps {
                echo hello
            }
        }
        stage('build') {
            steps {
                bat 'python --version'
            }
        }
    }
}
