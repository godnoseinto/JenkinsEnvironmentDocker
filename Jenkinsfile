pipeline {
    agent any
    tools{
        maven 'maven_3_8_6'
    }
    stages {
        stage('Build') {
            steps {
                dir("Curso-Microservicios/"){
                    sh "docker build -t microservicio ."
                }
            }
        }
    }
}