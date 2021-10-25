pipeline
{
agent any
 
 stages
 {
  stage('continuos download')
    {
     steps
     {
      git 'https://github.com/Mandara1189/Maven.git'       
     }
    }
    stage('continuos build')
    {
     steps
     {
      sh 'mvn package'     
     }
    }
 }
 }
