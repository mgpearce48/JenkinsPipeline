pipeline {
   agent none
   stages {
      stage('Hello') {
         agent {
            label 'agent'
         }
         steps {
            sh 'java -version'
            echo 'Get working directory'
            sh 'pwd'
         }
      }
      stage('More') {
         agent {
            label 'my-agent'
         }
         steps {
            echo 'Here is more...'
            sh 'docker compose version'
         }
      }
   }
}
