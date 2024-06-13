// jenkins excercise 2 to create standard pipeline with scripts
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh "sh build.sh"
             }
        }
        stage('Test') {
            steps {
                sh "sh test.sh"
            }
        }
        stage('Deploy') {
            steps {
                sh "sh deploy.sh"
            }
        }
    }
}