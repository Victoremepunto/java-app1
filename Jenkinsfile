pipeline {
    agent { any 'maven:3.3.3' }
    stages {
        stage('build') {
            steps {
                sh 'echo $HOSTNAME'
                sh 'mvn --version'
            }
        }
    }
}