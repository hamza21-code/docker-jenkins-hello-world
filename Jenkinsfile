Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'maven:3.8.4-openjdk-11-slim' } }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
            steps {
                 sh 'mvn --version'
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