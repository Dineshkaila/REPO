pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                sh 'exit 1'
            }
        }
    }

    post {
        always {
            echo 'Pipeline finished'
        }
        success {
            echo 'Pipeline succeeded'
        }
        failure {
            echo 'Pipeline failed'
        }
    }
}

