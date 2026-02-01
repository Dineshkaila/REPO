pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Dineshkaila/REPO.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Starting build...'
                sh '''
                  echo "Build running on Jenkins"
                  # Examples:
                  # mvn clean package
                  # npm install && npm run build
                  # python setup.py build
                '''
            }
        }
    }

    post {
        success {
            echo '✅ Build completed successfully'
        }
        failure {
            echo '❌ Build failed'
        }
    }
}

