pipeline {
    agent any
	
	 triggers { downstream(downstreamProjects: 'job1,job2', threshold: hudson.model.Result.SUCCESS) }
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
                sh 'echo "Success" '
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
