#!groovy

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building'
                powershell 'ls'
            }
        }
         stage('Test') {
            steps {
                echo 'Testing'
                powershell 'pwd'
            }
        }
         stage('Deploy Desarrollo') {
            steps {
                echo 'Testing'
                powershell 'dir'
            }
        }
         stage('Deploy QA') {
            steps {
                echo 'Test de Calidad'
                powershell 'cls'
            }
        }
         stage('Deploy Pre-Producción') {
            steps {
                echo 'Despliegue entorno pre-producción'
                powershell 'ls'
            }
        }
         stage('Deploy Producción') {
            steps {
                echo 'Despliegue entorno producción'
                powershell 'Get-Process'
            }
        }
    }
}
