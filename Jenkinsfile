pipeline {
    agent any

    stages {
        stage('GIT') {
            steps {
                git 'https://github.com/BhargavPetlu/Sample.git'
            }
        }
	stage('Python Run') {
	    steps {
	    	sh 'python sample.py'
    	    }
	}
    }
}
