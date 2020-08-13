pipeline {
  agent {
    node {
      label 'nodetest'
    }

  }
  stages {
    stage('node-env-init') {
      steps {
        sh 'npm  -v'
      }
    }

  }
}