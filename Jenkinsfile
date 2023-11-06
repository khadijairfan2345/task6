pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Add build commands here, for example:
                // sh 'make'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
                // Add test commands here, for example:
                // sh './run-tests.sh'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add deploy commands here, for example:
                // sh './deploy.sh'
            }
        }
    }

    post {
        success {
            echo 'Build succeeded!'
        }
        failure {
            echo 'Build failed!'
        }
    }
}
