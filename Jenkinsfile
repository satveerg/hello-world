pipeline {
    agent any
    parameters {
    choice choices: ['tetrapak-customerhub', 'tetrapak-publicweb'], description: '', name: 'CHOICE'
                }
    environment {
        DISABLE_AUTH = 'true'
        DB_ENGINE    = 'sqlite'
    }

    stages {
        stage('Build') {
            steps {
                sh 'printenv'
            }
        }
    }
}
