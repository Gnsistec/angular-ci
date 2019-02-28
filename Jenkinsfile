pipeline {
    agent  any 
    stages {
		stage('Install Npm') {
				steps {
					 bat 'npm install'
				}
			}
        stage('UnitTest') {
            steps {
                 bat 'ng test'
            }
        }
    }
}