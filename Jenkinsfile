pipeline {
  agent {
    node {
      label 'platform'
      customWorkspace '/code' 
    }
  }
   
  stages {
    stage('---compile---'){
      steps {
        sh "/jenkins/bin/pipe4"
      }
    }
    stage('---run---'){
      steps {
        sh "/jenkins/bin/pipe5"
      }
    }
    stage('---cleanup---'){
      steps {
        sh "/jenkins/bin/pipe6"
      }
    }
  }
}
