pipeline {
    agent any

    stages {
        stage('Start') {
            steps {
                sh 'ls'
            }
        }
        stage('Build') {
            steps {
                dir('.') {
                    sh 'ls'
                    build job: 'Jenkinsfile', wait: true
                }
            }
        }        
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
