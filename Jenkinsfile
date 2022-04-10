	pipeline {
		agent any

		stages {
		    stage('Checkout') {
		        steps {
					//checkout scm
				        echo "checkout stage"
					
		        }
		    }
			stage('Build') {
		        steps {
					//sh 'mvn install -DskipTests'
		        		echo "Build stage"
			}
			}
			stage('Test') {
		        steps {
					//sh 'mvn test'
				        echo "test stage"
		        }
			}
		}
	}
