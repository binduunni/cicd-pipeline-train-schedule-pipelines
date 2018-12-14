pipeline {
 agent any
 stages {
   stage ('Build') {
    steps {
      echo 'Build Running automation'
      sh './gradlew build --no-daemon'
      archiveartifacts artifacts 'dist/trainSchedule.zip'
    }
   }
 }
}
