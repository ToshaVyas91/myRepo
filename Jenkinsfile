pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}