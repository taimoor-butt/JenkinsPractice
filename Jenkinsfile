pipeline {
    agent any
    stages {
        stage('mvn clean') {
            steps {
                bat "mvn -f clean JenkinsPractice"
            }
        }
        stage('install') {
            steps {
                bat "mvn -f install JenkinsPractice"
            }
        }
        stage('test') {
            steps {
                bat "mvn -f test JenkinsPractice"
            }
        }
        stage('package') {
            steps {
                bat "mvn -f package JenkinsPractice"
            }
        }
    }
}