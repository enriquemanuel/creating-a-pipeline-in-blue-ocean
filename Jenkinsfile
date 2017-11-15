pipeline {
  agent any
  stages {
    stage('one step') {
      steps {
        build(job: 'test', wait: true)
        echo 'aaaaa'
      }
    }
  }
}