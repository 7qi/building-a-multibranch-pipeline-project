pipeline {
  agent {
    docker {
      image 'nginx'
      args 'latest'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'echo "Hello world!"'
      }
    }
  }
}