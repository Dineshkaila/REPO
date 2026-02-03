pipeline {
    agent any

    stages {
        stage('Success Stage') {
            steps {
                echo 'This stage will pass'
            }
        }

        stage('Failing Stage') {
            steps {
                sh 'exit 1'
            }
        }
    }
}

