pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
            }
        }
	stage("test") {
		      steps {
		      sh 'python test.py'
		      }
	}
    }
}