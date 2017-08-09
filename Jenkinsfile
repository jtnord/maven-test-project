pipeline {
	docker {
		image 'maven'
	}
	stages {
		stage('Build it') {
			echo "building project"
			sh "mvn install"
		}
	}
}