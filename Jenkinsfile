pipeline {
	agent any
    // agent {
        // label 'dockerNode'
    // }
    stages {
        stage('checkout') {
            steps {
		echo "${params.environment}"
                // sh returnStatus: true, script: 'docker --version'
            }
        }
    }
}
