pipeline {
    agent any

    stages {
    	stage(‘Hello’) {
	    steps {
	    	sh 'echo "Hello"'
	    }
	}
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                sh './jenkins/scripts/test.sh'
            }
        }
    }
}
