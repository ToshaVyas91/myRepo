pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''pipeline {
   agent any
    
   stages {
      stage(\'Say Hello\') {
         steps {
            echo \'Hello World!\'   
            sh \'java -version\'
         }
      }
   }
}'''
        }
      }
    }
  }