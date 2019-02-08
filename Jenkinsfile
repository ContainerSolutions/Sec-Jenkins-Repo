pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                dir ('.') { 
                  sh('ls -l')
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
