pipeline {
  agent any
  stages {
    stage('run') {
      steps {
        bat(script: 'echo %DATE%', encoding: 'date', label: 'date', returnStatus: true, returnStdout: true)
      }
    }

  }
}