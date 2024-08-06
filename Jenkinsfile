pipeline {
    agent any
    tools {nodejs "NODEJS"}
    stages {
        stage('Build') { 
            steps {
                sh 'yarn install' 
            }
        }
    }
}