pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'IarBuild.exe iar_test.ewp -build Debug -log all'
        echo 'Compile complete'
      }
    }

  }
}