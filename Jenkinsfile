pipeline {
  agent any
  stages {
    stage('mvn-version') {
      agent {
        docker {
          image 'maven:slim'
        }

      }
      steps {
        sh 'java -version'
      }
    }
  }
}