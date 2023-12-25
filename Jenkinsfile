pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Hello'
        dotnetBuild(project: 'Jenkins')
      }
    }

  }
}