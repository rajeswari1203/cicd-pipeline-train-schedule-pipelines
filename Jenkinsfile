pipeline {
  agent any
  stages {
  
  stage('build'){
   steps{
   echo 'running build'
   sh './gradlew build --nodeamon'
   archiveArtifacts artifacts: 'dest/trainSchedule.zip'
   }
  }
  }
  }
