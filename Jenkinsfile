pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'mvn compile'
      }
    }

  }
  environment {
    tools = 'Maven 3.9.4'
  }
}