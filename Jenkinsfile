pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/santanu603/sppedpro.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}
