pipeline {
    agent { dockerfile true }

    stages {
        stage('Build') {
            steps {
                echo 'hello'
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