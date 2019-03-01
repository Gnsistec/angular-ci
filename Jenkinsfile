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
					 bat 'ng t --watch=false'
				}
			}
		stage('UnitTest') {
				steps {
					 bat 'ng t --watch=false'
				}
			}
        stage('AngularBuild') {
				steps {
					 bat 'ng build --prod'
				}
        }		
    }
}