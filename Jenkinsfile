pipeline {
  agent {
    node {
      label 'master'
    }
    
  }
  stages {
    stage('ant-version') {
      steps {
        sh 'java -version'
      }
    }
  }
}