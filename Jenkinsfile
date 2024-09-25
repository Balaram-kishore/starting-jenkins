pipeline {
    agent {
        label 'AGENT-1'
    }
    options {
        
        timeout(time:30, unit: 'MINUTES')
        disableConcurrentBuilds()
    }

    stages {
        stage('Build') {
            steps {
                sh 'echo Building'
            }
        }
        stage('Test') {
            steps {
                sh 'echo testing'
                sh 'sleep 10'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo testing'
            }
        }
    }
}