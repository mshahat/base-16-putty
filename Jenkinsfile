pipeline {
  agent {
    node {
      label 'master'
    }
    
  }
  stages {
    stage('build') {
      agent {
        node {
          label 'master'
        }
        
      }
      environment {
        MAJOR_VERSION = '1'
      }
      steps {
        sh 'mvn --version'
      }
    }
  }
  environment {
    MAJOR_VERSION = '1'
  }
}