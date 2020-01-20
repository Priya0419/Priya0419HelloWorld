pipeline {
  agent any
  stages {
    stage('run') {
      steps {
        bat(script: 'echo %date%', encoding: 'date', label: 'date', returnStatus: true, returnStdout: true)
      }
    }

  }
}