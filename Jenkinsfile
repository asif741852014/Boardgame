pipeline {
    agent {label 'slave1'}
    tools {
        maven 'maven1'
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
