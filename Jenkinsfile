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
      steps {
        sh '''mvn --version
        '''
        echo 'hello from the other side'
        isUnix()
      }
    }
  }
}