pipeline {
	agent any 

	stages {
		stage('Build') {
			steps {
				sh 'mvn -B -DskipTests package'
			}
		}

		stage('deploy') {
			steps {
				sh 'mvn deploy'
			}
		}
	}
}



