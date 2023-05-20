// SCRIPTED

// DECLARATIVE
pipeline {
	agent any
	stages {
		stage('Build') {
			steps{
				echo "Build"
			}
		}
		stage('Test') {
			steps{
				echo "Build"
				
			}
		}
		stage('Integration Test') {
			steps{
				echo "Integration Test"
			}
		}
	}
	post {
		always {
			echo "I am awesome. I run always"
		}
		success {
			echo "I run when you are sucessful"
		}
		failure {
			echo "I run when you fail"
		}
	}
}
