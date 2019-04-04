pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'

                script {
		  codeBuilder = load 'codeBuilder.groovy'
                  codeBuilder.satveer()
                }
            }
        }
    }
}
