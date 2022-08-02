pipeline {
   agent {
      label 'agent'
   }
   stages {
      stage('Hello') {
         steps {
            docker('docker') { }
            sh 'java -version'
            echo 'Get working directory'
            sh 'pwd'
         }
      }
   }
}
