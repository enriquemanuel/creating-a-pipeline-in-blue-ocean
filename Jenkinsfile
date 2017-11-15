pipeline {
  agent {
    docker {
      image 'alpine'
      args 'latest'
    }
    
  }
  stages {
    stage('one step') {
      steps {
        build(job: 'enriqueme', wait: true)
      }
    }
  }
}