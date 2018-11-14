pipeline {
  agent any
  stages {
  
  stage('build'){
   steps{
   echo 'running build'
   sh './gradlew build --nodemon'
   archiveArtifacts artifacts 'dest/trainSchedule.zip'
   }
  }
  }
  }
