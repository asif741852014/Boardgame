pipeline {
    agent any
    tools {
        maven 'maven1'
    }
    stages {
        stage('compile') {
            steps {
                sh "mvn compile"
            }
        }
        stage('compile') {
            steps {
                sh "cat asif.txt"
            }
        }
        stage('test') {
            steps {
                sh "mvn test"
            }
        }
        stage('Hello') {
            steps {
                sh "mvn package"
            }
        }
    }
}
