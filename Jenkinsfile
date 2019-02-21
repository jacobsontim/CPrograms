pipeline {
  agent {
    node {
      label 'platform'
      
    }
  }
   
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
    stage('---cleanup---'){
      steps {
        sh "pwd"
      }
    }
  }
}
