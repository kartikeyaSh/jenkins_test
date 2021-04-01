pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
            }
        }
	stage("test") {
		      steps {
		      sh 'apt-get install python'
		      sh 'python test.py'
		      }
	}
    }
}