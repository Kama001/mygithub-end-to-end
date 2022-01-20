pipeline {
    agent {
        label 'dockerNode'
    }
    stages {
        stage('checkout') {
            steps {
                sh returnStatus: true, script: 'docker --version'
            }
        }
    }
}
