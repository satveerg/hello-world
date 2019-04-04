pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'

                script {
		  codeBuilder = load './codeBuilder.groovy'
                }
            }
        stage('Build') {
	    steps {
               script {
                     codeBuilder.satveer()
                      }
                    }
                       }
        }
    }
}
