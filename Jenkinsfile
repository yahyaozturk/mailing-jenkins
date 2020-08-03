pipeline {
  def code
  agent any
  stages {
    stage('Send Mail') {
      steps {
         code = load 'groovy/notificationManager.groovy'
         code.notifyEmail("SUCCESSFUL","yahyaozturk@gmail.com")
      }
    }
  }
}