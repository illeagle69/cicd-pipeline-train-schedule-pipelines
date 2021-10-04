pipeline {
  agent any
  stages {
    stage ('build) {
           steps {
             echo 'Running Jenkins Build Automation'
             sh './gradlew build --no-daemon'
             archiveArtifact artifacts: 'dist/trainSchedule.zip'
            }           
       }
    }
  }
