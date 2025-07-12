pipeline {
    agent any
    stages {
        stage('Build') { 
            stage('Test') {
                steps {
                    sh './jenkins/scripts/test.sh'
                }
            }
            steps {
                sh 'npm install' 
            }
        }
    }
}