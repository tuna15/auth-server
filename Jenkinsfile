pipeline {
  agent {
    docker {
      image 'tuna17/auth-server'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'docker build -t tuna17/auth-server'
      }
    }
  }
}