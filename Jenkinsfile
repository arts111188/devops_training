pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh "ls -ltr"
                sh "docker-compose up -d"
            }
        }
    }
}
