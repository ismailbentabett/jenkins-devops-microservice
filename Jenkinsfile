pipeline {
	agent {
		docker {
			image 'maven:3.6.3-jdk-11'
		}
	}
	stages {
		stage('Build') {
			steps {
				sh "mvn --version"

				echo "Build"
			}
		}
		stage('Test') {
			steps {
				echo "Test"
			}
		}
		stage('Deploy') {
			steps {
				echo "Deploy"
			}
		}
	}



}
