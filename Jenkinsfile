pipeline {
  agent any
  stages {
    stage('Send Mail') {
      steps {
        script {
         def code = load 'groovy/notificationManager.groovy'
         code.notifyEmail("SUCCESSFUL","yahyaozturk@gmail.com")
        }
      }
    }
  }
}