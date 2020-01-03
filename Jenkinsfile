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
              def props = readJSON text: '{ "key": "value" }'
              assert props['key'] == 'value'
              assert props.key == 'value'
       }      
    }
        stage('Deploy') {
            steps {
               sh 'sudo ./deploy.sh'
            }
        }
    }
}
                    







