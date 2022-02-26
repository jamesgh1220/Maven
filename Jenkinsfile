pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        build(job: 'JOB3', quietPeriod: 2, wait: true)
      }
    }

  }
}