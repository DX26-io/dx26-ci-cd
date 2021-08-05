pipeline {
  agent any
  stages {
    stage('Clean Up') {
      steps {
        sh "docker rmi $(docker images -q) --force"
      }
    }
  }
}
