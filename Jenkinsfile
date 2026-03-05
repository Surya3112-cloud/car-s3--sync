pipeline {
agent any

```
stages {
    stage('Clone Repository') {
        steps {
            git branch: 'main',
            url: 'https://github.com/Surya3112-cloud/car-s3--sync.git'
        }
    }

    stage('Deploy Static Site') {
        steps {
            sh '''
            echo "Deploying static website..."
            mkdir -p /var/www/html/car-site
            cp -r * /var/www/html/car-site/
            '''
        }
    }
}

post {
    success {
        echo 'Deployment successful!'
    }
    failure {
        echo 'Deployment failed!'
    }
}
```

}
