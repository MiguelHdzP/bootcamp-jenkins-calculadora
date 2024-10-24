pipeline {
  agent any

  tools {
    maven "maven 3.8.8"
  }

  stages {
    stage('Build') {
      steps {
        bat 'mvn -B -q package'
      }
    }
  }

}
