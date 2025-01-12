pipeline {
    agent any
    tools {
        maven 'maven3'
        jdk 'java18'
    }
    stages {
        stage('compile') {
            steps {
                sh "mvn compile"
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
