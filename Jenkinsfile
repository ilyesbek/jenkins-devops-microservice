//SCRIPTED

//DECLARATIVE
pipeline {
	    agent any
		stages {
			stage("Build") {
				steps {
						echo "Build"
				}
			}
		
		stage("Test") {
				steps {	
						echo "Test"
				}
			}
		
		stage("Integration Test") {
				steps {
						echo "Integration Test"
				}
			}
		} post {
			failure {
				echo ' I run when I fail'
			}
		}
}
