pipeline {
  agent any

  tools {
    maven "3.8.8"
  }

  stages {
    stage('Build') {
      steps {
        sh 'mvn -B -q package'
      }
    }
  }

}
