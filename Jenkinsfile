pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo 'Building.'
            }
        }
        stage('Test') { 
            steps {
                echo 'Testing.'
            }
        }
        stage('Deploy') { 
            steps {
                echo 'Deploying.'
            }
        }
        stage('Assemble') { 
            steps {
                echo 'Assemble.'
                sh './gradlew assemble'
            }
        }
        stage('Unit Test') { 
            steps {
                echo 'Test.'
                echo './gradlew test'
            }
        }
    }
}