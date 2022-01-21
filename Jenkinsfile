@Library('testlib', changelog=false) _

log.info 'Starting'
log.warning 'Nothing to do!'

pipeline {
    agent none
    
    stages {
        stage('Build') {
            steps {
                script {
                    def dur= time.duration
                    log.info 'Guillaume Starting'
                    log.warning 'Guillaume Nothing to do!'
                    log.info dur
                }
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
