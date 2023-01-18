pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build Steps'
                sleep 10
            }
        }
         stage('Test') {
            steps {
                echo 'Test steps'
            }
        }
         stage('Deploy') {
            steps {
                echo 'Deploy Steps'
                sleep 10
            }
        }
        stage('Docker') {
            steps {
                echo 'Image Steps'
            }
        }
    }
}
