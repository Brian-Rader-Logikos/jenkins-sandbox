#!groovy
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Building...'
                sh 'python --version'
            }
        }
        stage('test') {
            steps {
                echo 'Testing...'
            }
        }
    }
}
