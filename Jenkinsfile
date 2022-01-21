@Library('testlib') _

log.info 'Starting'
log.warning 'Nothing to do! '

pipeline {
    agent none
    
    stages {
        stage('Build') {
            steps {
                script {
                    time.duration()
                    log.info 'Guillaume Starting '
                    log.warning 'Guillaume Nothing to do!'
                }
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying.... OK'
            }
        }
    }
}
