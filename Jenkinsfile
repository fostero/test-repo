pipeline {
    agent none
    stages {
        stage('build') {
            agent {
                docker { image 'terraform:0.12.8' }
            }
            steps {
             terraform commandArguments: 'help', commandName: 'terraform', label: ''
            }
        }
    }
}