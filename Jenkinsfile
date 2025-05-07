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
                echo 'Building the project...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
