pipeline {
    agent {
    docker {
        image 'jenkins/jnlp-slave'
        label 'appkub'
        args  '-v /tmp:/tmp'
    }
}
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
