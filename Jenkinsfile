pipeline {
  agent {
    docker {
      image 'nosw:6-alpine'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install '
      }
    }
  }
}