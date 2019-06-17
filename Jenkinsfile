pipeline {
    agent any
	
	
    stages {
         stage(' Pre-Test') {
            steps {
                sh 'echo "Success" '
            }
         }
        stage('Test') {
            steps {
                sh 'echo "Success" '
            }
        }
        stage('Build') {
            steps {
                build job: '/job1'
            }
        }
        stage('CheckOut') {
            steps {
                sh 'echo "Success" '
            }
        }
        stage('Release') {
            steps {
                sh 'echo "Success" '
            }
        }


	}

}
