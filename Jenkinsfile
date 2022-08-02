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
            sh 'docker --version'
            sh 'docker ps -a'
            sh 'docker images'
            sh 'docker volume ls'
         }
      }
   }
}
