def externalMethod
pipeline {
  agent any
  stages {
    stage('Send Mail') {
      steps {
         externalMethod = load("groovy/notificationManager.groovy")
         externalMethod.notifyEmail("SUCCESSFUL","yahyaozturk@gmail.com")
      }
    }

  }
}