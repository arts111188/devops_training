pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh "sh cd /root/test/"
                sh "docker-compose up -d"
            }
        }
    }
}
