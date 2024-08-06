pipeline {
    agent any
    tools {nodejs "NODEJS"}
    stages {
        stage('Build') { 
            steps {
              script {
                    sh 'yarn install'
                }
            }
        }
    }
}