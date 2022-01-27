pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'sudo docker build -t hello-word-php-apache .'
            }
        }
        stage('Deploy') {
            steps {
                sh 'sudo docker run -p 80:80 hello-word-php-apache'
            }
        }
    }
}
