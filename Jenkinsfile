pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh "cd /root/test/"
                sh "docker-compose up -d"
            }
        }
    }
}
