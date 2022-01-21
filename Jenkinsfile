pipeline {
    agent none
    @Library('testlib') _
    
    stages {
        stage('Build') {
            steps {
                echo libCOMMON.log("hello un message ici et la")
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
