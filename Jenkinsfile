pipeline {
  agent {
    docker {
      image 'node:14.8.0-alpine3.10'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('node-env-init') {
      steps {
        sh 'npm  -v'
      }
    }

    stage('build') {
      steps {
        sh 'npm -v'
      }
    }

  }
}