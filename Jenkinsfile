pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat(script: 'IarBuild.exe iar_test.ewp -build Debug -log all', returnStatus: true)
        echo 'Compile complete'
      }
    }

  }
}