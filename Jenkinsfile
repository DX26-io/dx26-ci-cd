pipeline {
  agent any
  stages {
    stage('Clean Up') {
      steps {
//         sh 'docker rmi $(docker images -q) --force'
        sh 'chmod 776 /var/run/docker.sock'
      }
    }
  }
}
