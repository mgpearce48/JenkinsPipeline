pipeline {
   agent {
      label 'agent'
   }
   stages {
      stage('Hello') {
         steps {
            docker('docker-latest')
            sh 'java -version'
            echo 'Get working directory'
            sh 'pwd'
            sh 'docker --version'
         }
      }
   }
}
