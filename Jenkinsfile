pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!'
		sh label: '', script: 'python3 --version'
            }
        }
    }
}