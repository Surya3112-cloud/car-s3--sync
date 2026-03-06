pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git 'https://github.com/Surya3112-cloud/car-s3--sync.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building the project..."
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application..."
            }
        }

    }
}
