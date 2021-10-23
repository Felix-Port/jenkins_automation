pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building.. More'
            }
        }
        stage('Test') {
            when {
                expression {
                    BRANCH_NAME == 'main'
                }
            }
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
