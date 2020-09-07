pipeline {
    agent any
    tools {
            maven 'apache-maven-3.5.0'

        }

    stages {
        stage ('Compile Stage') {
            steps {
                bat 'mvn clean compile'
            }
        }

        stage ('Testing Stage') {
            steps {
                bat 'mvn test'
            }
        }
    }
}






