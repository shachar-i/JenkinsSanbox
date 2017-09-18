pipeline {
    agent any
    stages {
      stage('debug') {
            steps {
                echo "Git Configuration:"
                bat 'git status'
                bat 'git log -n 5'
                bat 'git remote -v'
                bat 'git branch'
                bat 'git config user.name'
                bat 'git config user.email'
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
