@Library('learning-library')
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                build.build()
            }
        }
    stages {
        stage('sonar') {
            steps {
                build.sonarrun()
            }
                       }
           }    
    }
}
