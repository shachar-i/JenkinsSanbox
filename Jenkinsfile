pipeline {
    agent any
    stages {
      stage('debug') {
            steps {
                echo "hello"
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
