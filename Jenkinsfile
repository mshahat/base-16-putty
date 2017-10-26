pipeline {
  agent {
    node {
      label 'mshahat-rmbp-mvn-version'
    }
    
  }
  stages {
    stage('mvn version') {
      steps {
        sh 'mvn --version'
      }
    }
  }
}