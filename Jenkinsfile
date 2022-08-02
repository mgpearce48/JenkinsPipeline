pipeline {
   agent {
      label 'agent'
   }
   tools {
      dockerTool 'latest'
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
