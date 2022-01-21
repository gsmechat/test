@Library('testlib') _

log.info 'Starting'
log.warning 'Nothing to do!'

pipeline {
    agent none
    
    stages {
        stage('Build') {
            steps {
                log_info "hello un message ici et la"
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
