pipeline {
  agent {
    node {
      label 'master'
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