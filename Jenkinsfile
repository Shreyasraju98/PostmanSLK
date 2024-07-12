pipeline {
    agent any

    stages {
        stage('Clean') {
            steps {
                echo 'Cleaned'
                bat '''cd..
                       cd..
                       cd..
                       cd..
                       cd..
                       cd C:\\Jenkins
                       rmdir Temp1'''
            }
        }
        stage('BYE') {
            steps {
                echo 'Bye World'
            }
        }
    }
}