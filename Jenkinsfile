pipeline {
    agent any
    stages {
        stage('mvn clean') {
            steps {
                bat "mvn clean -p JenkinsPractice"
            }
        }
        stage('install') {
            steps {
                bat "mvn install -p JenkinsPractice"
            }
        }
        stage('test') {
            steps {
                bat "mvn test -p JenkinsPractice"
            }
        }
        stage('package') {
            steps {
                bat "mvn package -p JenkinsPractice"
            }
        }
    }
}