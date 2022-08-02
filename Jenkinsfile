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
      stage('Again') {
         agent {
             docker {
                 image 'node:lts-buster-slim'
                 args '-p 3000:3000'
//                  reuseNode true
             }
         }
         steps {
            echo 'And again...'
            sh 'ls -la'
         }
      }
   }
}
