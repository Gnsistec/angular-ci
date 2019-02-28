pipeline {
    agent  any 
    stages {
		stage('Install Npm') {
				steps {
					 bat 'npm install'
				}
			}
        stage('AngularBuild') {
				steps {
					 bat 'ng build'
				}
        }		
    }
}