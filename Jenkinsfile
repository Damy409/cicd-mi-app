pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/Damy409/cicd-mi-app.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean package'
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