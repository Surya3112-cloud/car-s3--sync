pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git branch: 'main',
                url: 'https://github.com/Surya3112-cloud/car-s3--sync.git'
            }
        }

        stage('Build') {
            steps {
                echo "Build Stage"
            }
        }

        stage('Test') {
            steps {
                echo "Test Stage"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploy Stage"
            }
        }

    }
}
