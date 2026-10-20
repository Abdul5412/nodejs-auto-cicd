pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out Node.js project'
            }
        }

        stage('Test') {
            steps {
                sh 'node --check app.js'
                sh 'npm test'
            }
        }

        stage('Build') {
            steps {
                echo 'Node.js application build completed'
            }
        }
    }
}
