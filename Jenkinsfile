pipeline {
    agent {label 'Linux'}
    stages {
        stage('Checkout') {
            steps {
                echo 'Hello, Maven'
                git url: 'https://github.com/arts111188/devops_training.git'
            }
        }
        stage('Create folde'){
           steps {
           folder('project-a') {
           displayName('Project A')
           description('Folder for project A')
       }      
    }
}
        stage('Deploy') {
            steps {
               sh 'sudo ./deploy.sh'
            }
        }
    }
}
                    







