pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/PraveenTej2022/JenkinsRepo1.git'
            }
        }
        stage('Build') {
            steps {
                sh 'Building the project...'
            }
        }
        stage('Test') {
            steps {
               sh 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                sh 'Deploying...'
            }
        }
    }
}
