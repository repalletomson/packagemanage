pipeline {
  agent any
  stages {
    stage('pip install numpy') {
      steps {
        bat 'py -m pip install -r requirement.txt'
      }
    }
  }
}
