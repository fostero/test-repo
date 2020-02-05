pipeline {
    agent { label 'docker' }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
		sh 'mvn --help'
            }
        }
    }
}