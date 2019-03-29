pipeline {
  agent any
  stages {
    stage('prepare') {
      steps {
        deleteDir()
      }
    }
    stage('build') {
      steps {
        isUnix()
      }
    }
  }
}