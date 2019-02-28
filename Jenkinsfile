pipeline {
    agent  any 
    stages {
        stage('build') {
            steps {
                git poll: true, url 'https://github.com/Gnsistec/angular-ci.git'
            }
        }
    }
}