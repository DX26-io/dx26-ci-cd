pipeline {
  agent any
  stages {
    stage('Clean Up') {
      steps {
        sh 'docker rmi $(docker images -q) --force'
        sh 'sudo chmod 776 /var/run/docker.sock'
      }
    }
  }
}
