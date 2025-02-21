pipeline {
    agent {
        dockerContainer { image 'node:22.13.0-alpine3.21' }
    }

    stages {
        stage('test') {
            steps {
                sh 'node ./index.js'
            }
        }
    }
}
