pipeline{
 agent any
 stages {
   stage ('Build'){
     steps{
       echo 'Running build automation'
       sh './gradeew build --no-daemon'
       archiveArtifacts artifacts: 'dist/trainSchedule.zip'
     }
   }
 }   
}
