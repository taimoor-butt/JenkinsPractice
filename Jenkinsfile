pipeline {
    agent any
    stages {
//         stage('mvn clean') {
//             steps {
//                 bat "mvn clean -f JenkinsPractice"
//             }
//         }
        stage('install') {
            steps {
                bat "mvn install -f JenkinsPractice"
            }
        }
        stage('test') {
            steps {
                bat "mvn test -f JenkinsPractice"
            }
        }
        stage('package') {
            steps {
                bat "mvn package -f JenkinsPractice"
            }
        }
    }
}