pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
            }
        }
	stage('Stage 2') {
	    steps {
	    	echo 'hello python'
	        sh 'python test.py'
	    }
	}
    }
}