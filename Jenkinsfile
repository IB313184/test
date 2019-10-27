pipeline {
  agent {
    node {
      label 'build'
    }

  }
  stages {
    stage('error') {
      steps {
        build '2'
      }
    }
  }
}