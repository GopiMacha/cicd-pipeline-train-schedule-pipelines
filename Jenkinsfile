pipeline{
agent any
  stages{
    stage("build"){
      steps{
      echo "hi from jenkins"
        sh echo "hi from shell"
        sh ./gradlew build
        archiveArtifacts artifacts:'dist/trainSchedule.zip'
      }
    }
  }
}
