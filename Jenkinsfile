//SCRIPTED

//DECLARATIVE
pipeline {
	// agent any
	agent { docker { image 'maven:3.8.4'} }
	stages {
		stage('Build') {
			steps {
				echo 'mvn --version'
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
