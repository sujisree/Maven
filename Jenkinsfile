pipeline {
    agent any
    stages {

        stage('clean') {
            steps {
                sh "mvn clean "
            }
        }
       
        stage('validate') {
            steps {
                sh "mvn validate "
            }
        }
       
        stage('build') {
            steps {
                sh "mvn package "
            }
        }
    }
}
