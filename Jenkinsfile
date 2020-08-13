pipeline {
  agent any
  stages {
    stage('node-env-init') {
      steps {
        sh 'docker pull postman/newman:4.5-alpine'
        sh 'docker run  -t postman/newman:4.5-alpine run test.postman_collection.json'
      }
    }

  }
}