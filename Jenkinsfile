pipeline {
    agent { docker { image 'node:16.13.1-alpine' } }
    stages {
        stage('test') {
          steps {
            echo ' ---- Test ----'
          }
        }
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}
