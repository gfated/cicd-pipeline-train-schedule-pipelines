pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Runing build automation mate'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts 'dist/trainSchedule.zip'
      }
    }
  }
}
