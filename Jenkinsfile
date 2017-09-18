pipeline {
    agent any
    stages {
      stage('debug') {
            steps {
                echo "hello 2"
                bat 'git status'
            }
        }
        stage('build') {
            steps {
                bat 'python --version'
                bat 'python test.py'
                echo "done"
            }
        }
    }
}
