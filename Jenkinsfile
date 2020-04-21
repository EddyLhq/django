pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build(job: 'build', quietPeriod: 1, wait: true, propagate: true)
      }
    }

    stage('review') {
      steps {
        sleep 2
      }
    }

  }
}