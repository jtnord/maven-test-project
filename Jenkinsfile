pipeline {
	agent {
		docker {
			image 'maven'
			label 'docker'
		}
	}
	stages {
		stage('Build it') {
			steps {
				echo "building project"
				sh "mvn install"
			}
		}
	}
}