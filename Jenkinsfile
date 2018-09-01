
pipeline {
    agent any

    environment {
        CI = 'true'
    }

    stages {
        stage('Test') {
            steps {
                echo 'test'
            }
        }

        stage('Build') {
            steps {
                echo 'build'
            }
        }

        stage('Deployment') {
            steps {
                echo 'deployment'
            }
        }
    }
}
