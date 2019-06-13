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
properties([
  pipelineTriggers([
    downstream(
      threshold: 'SUCCESS',
      downstreamProjects: '../job1'
    )
  ])
])	
	
}
