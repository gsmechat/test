pipeline {
    agent none
    @Library('testlib')_
    
    stages {
        stage('Build') {
            steps {
                echo 'Building.. ici'
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
