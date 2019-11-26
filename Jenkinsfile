pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''CD C:\\Program Files (x86)\\Jenkins\\workspace\\test-code_master
IarBuild.exe iar_test.ewp -build Debug -log all
echo \'done\''''
        echo 'Compile complete'
      }
    }

  }
}