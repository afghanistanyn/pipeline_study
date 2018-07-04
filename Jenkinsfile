pipeline {
  agent {
    node {
      label '*'
    }

  }
  stages {
    stage('deploy choice') {
      steps {
        input(message: 'which env you want deploy to', ok: 'go', submitter: 'test,enpr', submitterParameter: 'SERVER')
      }
    }
  }
}