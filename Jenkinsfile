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
		      python test.py
		      }
	}
    }
}