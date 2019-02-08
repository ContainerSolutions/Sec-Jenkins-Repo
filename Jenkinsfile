pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                "ls -l".execute().text
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
