pipeline {
    agent any
    stages {
        stage('Check windows') {
            steps {
                echo 'Hello windows World'
                bat 'docker info'
            }
        }

        stage('Check Linux') {
                    steps {
                        echo 'Hello linux World'
                        sh 'docker info'
                    }
        }
    }
}
