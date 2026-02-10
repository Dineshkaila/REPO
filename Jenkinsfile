pipeline {
    agent any

    stages {
        stage('This one Triggered by Github Webhook') {
            steps {
                echo "Build triggered automatically by GitHub webhook"
            }
        }
<<<<<<< HEAD

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
=======
>>>>>>> 7b8b77b8781da8aeb1dddd1ec736b355929d3aaa
    }
}

