pipeline {
    agent any
    stages {
        stage('Clonar Repositorio') {
            steps {
                echo "Clonando el repositorio: ${env.GIT_URL}"
                // Se asume que Jenkins ya clonó el repo gracias al SCM configurado
            }
        }
        stage('Build') {
            steps {
                echo 'Iniciando fase de Build ...'
                echo 'Artefacto de software creado.'
            }
        }
        stage('Test') {
            steps {
                echo 'Iniciando fase de Test ...'
                echo 'Ejecutando pruebas unitarias y de integración.'
                echo 'Pruebas finalizadas con éxito.'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Iniciando fase de Deploy (Simulado)...'
                echo 'Despliegue exitoso al ambiente de Staging.'
            }
        }
    }
}