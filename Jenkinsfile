pipeline {
  agent any
  stages {
    stage('Send Mail') {
      steps {
        emailext(subject: 'Hello', body: 'Hello', to: 'yahyaozturk@gmail.com')
      }
    }

  }
}