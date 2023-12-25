pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Hello'
        dotnetBuild(project: 'Jenkins.sln', option: 'Release', sdk: '7.400')
      }
    }

  }
}