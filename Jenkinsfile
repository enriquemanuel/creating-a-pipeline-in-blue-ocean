pipeline {
  agent any
  stages {
    stage('one step') {
      agent any
      steps {
        build(job: 'job1', wait: true)
      }
    }
  }
}