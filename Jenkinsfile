pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh "pwd"
                sh "cd /root/test"
                sh "docker-compose up -d"
            }
        }
    }
}
