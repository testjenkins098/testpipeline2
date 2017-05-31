pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                build("Solution");
		build("Testv1");
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
