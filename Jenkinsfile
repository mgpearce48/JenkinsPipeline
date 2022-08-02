pipeline {
   agent {
      label 'agent'
   }
   tools {
      dockerTool 'docker'
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
