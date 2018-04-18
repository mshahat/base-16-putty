pipeline {
  agent {
    docker {
      image 'maven:slim'
    }

  }
  stages {
    stage('mvn-version') {
      agent {
        docker {
          image 'maven:slim'
        }

      }
      steps {
        sh 'mvn --version'
      }
    }
  }
}