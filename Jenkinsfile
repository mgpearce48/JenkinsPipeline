pipeline {
   agent {
      label 'agent'
   }
   tools {
      docker 'latest'
   }
   stages {
      stage('Hello') {
         steps {
            sh 'java -version'
            echo 'Get working directory'
            sh 'pwd'
         }
      }
   }
}
