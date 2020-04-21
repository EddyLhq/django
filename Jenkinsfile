pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build(job: 'bbb', quietPeriod: 1, wait: true)
      }
    }

    stage('review') {
      steps {
        sleep 2
      }
    }

  }
}