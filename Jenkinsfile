@Library('testlib') _

log.info 'Starting'
log.warning 'Nothing to do! '

pipeline {
    agent {
        label 'agent1'
    }
    
    stages {
        stage('Build') {
            steps {
                script {
                    def dur = time.duration()
                    log.info 'Guillaume Starting '
                    log.warning 'Guillaume Nothing to do!'
                    //log.info "${dur}"
                    def browsers = ['chrome', 'firefox']
                    for (int i = 0; i < browsers.size(); ++i) {
                        echo "Testing the ${browsers[i]} browser"
                    }
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
