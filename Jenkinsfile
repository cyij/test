pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('node-env-init') {
      steps {
        sh 'sh \'npm install\''
      }
    }

  }
}