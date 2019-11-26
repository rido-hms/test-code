pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'dir'
        sh 'CD "C:\\Program Files (x86)\\Jenkins\\workspace\\test-code_master"'
        sh 'IarBuild.exe "iar_test.ewp" -build Debug -log all'
        echo 'Compile complete'
      }
    }

  }
}