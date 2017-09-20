pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Build') {
            steps {
                sh 'node --version'
            }
        }
        stage('Test') {
            steps {
                sh 'echo Test..'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo Deploy..'
            }
        }
    }
}
