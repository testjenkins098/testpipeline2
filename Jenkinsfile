pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                build("Solution");
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Test"'
            }
        }
        stage('Prod') {
            steps {
                sh 'echo "Prod"'
            }
        }
    }
}
