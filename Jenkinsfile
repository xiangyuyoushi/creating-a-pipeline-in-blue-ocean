pipeline {
  agent {
    docker {
      image 'node:12.16.2'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }

  }
}
