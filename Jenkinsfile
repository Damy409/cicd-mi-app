pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Build exitoso (simulado)'
            }
        }

        stage('Static Analysis (SonarQube)') {
            steps {
                echo 'Análisis de código con SonarQube (simulado)'
            }
        }

        stage('Quality Gate') {
            steps {
                script {
                    echo 'Validando calidad...'
                    // Simulación: pasa
                }
            }
        }

        stage('Docker Build') {
            steps {
                echo 'Docker build simulado'
            }
        }

        stage('Security Scan (Trivy)') {
            steps {
                echo 'Escaneo de vulnerabilidades (simulado)'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy simulado'
            }
        }
    }

    post {
        always {
            echo 'Limpiando entorno...'
        }
        failure {
            echo 'Pipeline falló'
        }
        success {
            echo 'Pipeline exitoso'
        }
    }
}