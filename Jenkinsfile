pipeline {
    agent { docker { image 'node:16.13.1-alpine' } }
    stages {
        stage('build') {
            steps {
                //bat 'node --version'
                bat 'echo "hej"; exit 1'
                bat 'node app.js'
            }
        }
        stage('test') {
            steps {
                bat 'echo "testing"; exit 1'
            }
        }
    }
}
