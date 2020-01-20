pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        git(url: 'https://github.com/Priya0419/Priya0419HelloWorld.git', branch: 'build', changelog: true, poll: true)
      }
    }

    stage('tst') {
      steps {
        echo 'echo %done%'
      }
    }

    stage('run') {
      steps {
        bat(script: 'echo %date%', encoding: 'date', label: 'date', returnStatus: true, returnStdout: true)
      }
    }

  }
}