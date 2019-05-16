@Library('library-roche') _
pipeline {
    agent none
    stages {
    stage ('Example') {
        steps {
            script { 
                log.info 'Starting'
                log.warning 'Nothing to do!'
                // sayHello.call
                sh 'echo "checking multipipeline trigger"'
            }
        }
    }
}
}
