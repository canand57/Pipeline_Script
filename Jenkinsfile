pipeline{
 agent any
  stages{
    stage('Git'){
      steps{
       git 'https://github.com/canand57/Pipeline_Script.git'
           }
             }
    stage('build'){
      steps{
       bat 'Build.bat'
      } 
    }
   stage('Deploy'){
      steps{
       bat 'Deploy.bat'
      } 
    }
   stage('unit'){
      steps{
       bat 'Unit.bat'
      } 
    }
  }
}
    
