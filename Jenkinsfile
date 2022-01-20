pipeline {
    agent any
    environment { 
        TEST = 'hello world!t'
    }
    stages {
        stage('Example') {
            environment { 
                TEST2 = '-g'
            }
            steps {
                sh 'printenv'
            }
        }
    }
}
