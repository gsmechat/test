libraries {
    lib('testlib')
}

pipeline {
    agent none
    
    stages {
        stage('Build') {
            steps {
                libCOMMON.log_info("hello un message ici et la")
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
