pipeline {
  agent any
  stages {
    stage('Send Mail') {
      steps {
         def externalMethod = load("groovy/notificationManager.groovy")
         externalMethod.notifyEmail("SUCCESSFUL","yahyaozturk@gmail.com")
      }
    }

  }
}