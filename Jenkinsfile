pipeline {
    agent { docker { image 'php' } }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
		sh 'echo build is done :D'
            }
        }
    }
}
