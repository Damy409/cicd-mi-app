pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Build exitoso (simulado)'
            }
        }

        stage('Docker Build') {
            steps {
                sh 'docker build -t mi-app:latest .'
            }
        }

        stage('Test') {
            steps {
                echo 'Tests ejecutados'
            }
        }

        stage('Deploy') {
            steps {
                sh 'docker run -d -p 80:80 mi-app:latest'
            }
        }
    }
}