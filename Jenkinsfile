pipeline {
  agent any
  stages {
    stage('---compile---'){
      steps {
        sh "g++ -o hw hw.cpp"
      }
    }
    stage('---run---'){
      steps {
        sh "./hw"
      }
    }
  }
}
