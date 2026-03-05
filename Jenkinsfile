pipeline {
    agent any

    stages {

        stage('Clone Code') {
            steps {
                git 'https://github.com/Surya3112-cloud/car-s3--sync.git'
            }
        }

        stage('Deploy Website') {
            steps {
                sh '''
                sudo rm -rf /var/www/html/*
                sudo cp -r * /var/www/html/
                '''
            }
        }

    }
}
