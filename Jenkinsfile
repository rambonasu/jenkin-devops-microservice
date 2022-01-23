//SCRIPTED

//DECLARATIVE
pipeline {
	// agent any
	agent { Docker { image 'maven:3.8.4'} }
	stages {
		stage('Build') {
			steps {
				sh 'maven --version'
				echo "Build"
			}
		}
	stage('Test') {
        steps {
	        echo "Test"
		}
	}
	stage('Integration Test') {
			steps {
	            echo "Integration Test"
			}
		}
	}
}	
