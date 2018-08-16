pipeline {
  agent {
    dockerfile {
      filename 'dockerfile'
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