pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'echo Hei på deg'
                sh 'echo update 10:48'
                sh 'echo update 07:53'
            }
        }
    }
}
