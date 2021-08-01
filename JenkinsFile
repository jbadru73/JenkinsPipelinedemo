pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the Application'
            }
        }
        stage('UnitTest') {
            steps {
                echo 'Testing the Application'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to QA'
            }
        }
        stage('Release') {
            steps {
                echo 'Releasing to Production'
            }
        }
    }
}
