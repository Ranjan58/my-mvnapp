pipeline {
    agent any
    stages {
        stage('----clean----') {
            steps withmaven{
                sh "mvn clean"
            }
        }
        stage('----test----') {
            steps withmaven{
                sh 'mvn test'
            }
        }
        stage('----package----') {
            steps withmaven{
                sh 'mvn package'
            }
        }
    }
}
