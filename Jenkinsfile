pipeline {
  agent {
    kubernetes {
        label:       
kind: Pod
metadata:
  name: jenkins-agentkub
  nameSpace: jenkinskub
spec:
  containers:
  - name: gradle
    image: gradle:jdk8
    securityContext:
      runAsUser: 0
    command:
    - cat
    tty: true
   }
 }
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
            }
        }
    }
}
