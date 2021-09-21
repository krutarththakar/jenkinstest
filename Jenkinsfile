pipeline {
    agent {
    docker {
        image 'jenkins/jnlp-slave'
        label 'appkub'
        args  '-v /tmp:/tmp'
        idleMinutes 5
    }
}
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
