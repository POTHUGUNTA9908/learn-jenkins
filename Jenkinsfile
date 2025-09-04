pipeline {
    agent {
        label 'AGENT-1'
    }
    stages {
        stage('Build') {
            steps {
               sh 'echo this bulid'
            }
        }
        stage('Test') {
            steps {
                sh 'echo this test'
            }
        }
        stage('Deploy') {
            steps {
               sh 'echo this deploy'
            }
        }
    }
}

