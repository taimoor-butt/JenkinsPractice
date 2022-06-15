pipeline {
    agent any
    stages {
        stage('mvn clean') {
            steps {
                bat "mvn -X clean JenkinsPractice"
            }
        }
        stage('install') {
            steps {
                bat "mvn install JenkinsPractice"
            }
        }
        stage('test') {
            steps {
                bat "mvn test JenkinsPractice"
            }
        }
        stage('package') {
            steps {
                bat "mvn package JenkinsPractice"
            }
        }
    }
}