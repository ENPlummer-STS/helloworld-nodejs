pipeline {
  agent none
  stages {
    stage('Say Hello') {
      agent {label 'nodejs'}
      steps {
        echo 'Hello World!'   
        sh 'java -version'
      }
    }
  }
}
