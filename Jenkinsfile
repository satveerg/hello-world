
@Library('learning-library') _

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script{
                build.build()
                }
            }
        }
        stage('sonar') {
            steps {
                script{
                build.sonarrun()
                }
            }
        }
    }    
}
