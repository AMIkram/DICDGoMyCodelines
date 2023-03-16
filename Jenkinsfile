pipeline{
  agent any
  stages{
    stage('build'){
      steps{
        
        echo'Running build automation'
        sh'./gradle wrapper'
        sh './gradlew build --no -daemon'
        archiveArtifacts artifacts:'dist/CiCdGoMyCode.zip'
      }}}}
