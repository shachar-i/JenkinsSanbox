pipeline {
    agent { docker 'python:3.5.1' }
    stages {
      stage('debug') {
            steps {
                echo 'Building..'
                echo 'Building2..'
            }
        }
        stage('build') {
            steps {
                bat 'python --version'
            }
        }
    }
}
