pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
	},
	stage('Hello World') {
	    steps{
		sh 'Hello World!!!'
	    }
        }
    }
}
