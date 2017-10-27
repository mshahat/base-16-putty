pipeline {
  agent {
    docker {
      image 'maven:3-alpine'
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
        sh '''mvn --version
        '''
      }
    }
  }
}