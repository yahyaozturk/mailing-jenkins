pipeline {
  agent any
  stages {
    stage('Send Mail') {
      steps {
         def externalMethod = load("groovy/notificationManager.groovy")
         // Call the method we defined in file1.
         externalMethod.notifyEmail("SUCCESSFUL","yahyaozturk@gmail.com")
      }
    }

  }
}