// SCRIPTED

// DECLARATIVE
pipeline {
	// agent any
	agent { docker { image 'maven:3.6.3' } }

	stages {
		stage('Build') {
			steps{
				sh 'mvn --version'
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
