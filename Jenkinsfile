pipeline {
    agent any

    stages {
        stage('CodeScan') {
            steps {
                sh 'trevy --version'
               
            }
        }

        stage('dockerImageBuild') {
            steps {
                sh 'docker -v'
            }
        }

        stage('createfile') {
            steps {
                sh 'docker ps'
            }
        }
    }
}
