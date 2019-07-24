
@Library('learning-library') _
import com.nbs.*
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
