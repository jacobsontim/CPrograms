pipeline {
  agent {
    node {
      label 'platform'
    }
  }
   
  stages {
    stage('---compile---'){
      steps {
        sh "/jenkins/bin/pipe4.sh"
      }
    }
    stage('---run---'){
      steps {
        sh "/jenkins/bin/pipe5.sh"
      }
    }
    stage('---cleanup---'){
      steps {
        sh "/jenkins/bin/pipe6.sh"
      }
    }
  }
}
