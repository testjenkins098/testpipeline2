pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                build(job: "Solution", config: "release");
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
