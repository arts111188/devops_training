pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh "docker run --name=test-mysql --env=//"MYSQL_ROOT_PASSWORD=mypassword" mysql//"
            }
        }
    }
}
