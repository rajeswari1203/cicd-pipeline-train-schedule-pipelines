pipeline {
  agent any
  stages {
  
  stage('build'){
   steps{
   echo 'running build'
   sh './gradlew build --nodaemon'
   archiveArtifacts artifacts: 'dest/trainSchedule.zip'
   }
  }
  }
  }
