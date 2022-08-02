pipeline {
   agent {
      label 'agent'
   }
   tools {
     Docker 'docker-latest'
    }      
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
