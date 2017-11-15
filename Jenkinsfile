pipeline {
  agent any
  stages {
    stage('one step') {
      steps {
        build(job: 'enriqueme', wait: true)
        echo 'aaaaa'
      }
    }
  }
}