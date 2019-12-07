pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh "pwd"
                sh "cd /var/lib/jenkins/workspace/"
                sh "docker-compose up -d"
            }
        }
    }
}
