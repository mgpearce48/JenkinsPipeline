pipeline {
   agent {
      label 'agent'
   }
   stages {
      stage('Hello') {
         steps {
            Docker('docker-latest') { sh 'docker --version' }
            sh 'java -version'
            echo 'Get working directory'
            sh 'pwd'
         }
      }
   }
}
