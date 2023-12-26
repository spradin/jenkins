pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Hello'
        dotnetBuild(project: 'Jenkins.sln', option: 'Release', framework: '7.0.400')
      }
    }

  }
}