pipeline {
	agent any
	
	stages {
		stage('Test') {
			steps {
				echo 'Perform unit tests here'
			}
		}
		stage('Build') {
			steps {
				echo 'Build Docker image and tag here'
			}
		}
		stage('Push Image') {
			steps {
				echo 'Push Docker image to DockerHub'
			}
		}
	}
}
