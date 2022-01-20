pipeline {
    agent { docker 'maven:3.8.1-adoptopenjdk-11' } 
    stages {
        stage('Example Buildc') {
            steps {
                sh ' mvn -B clean verify'
            }
        }
    }
}
