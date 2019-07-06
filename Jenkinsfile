pipeline {

  agent any
  stages {
   stage {'Build'} {
    steps {
      echo 'Muhammad Asim Arain Running Build Automation'
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip' 
    
    }
   
   
   }
  
  
  
  
  
  }



}
