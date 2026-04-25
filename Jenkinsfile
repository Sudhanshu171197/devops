pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application'
                sh ls
                sh pwd
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application'
            }
        }
    }
}
