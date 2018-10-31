pipeline{
  agent any
  stage('---clean---'){
    steps{
      sh "rm -rf CPrograms"
    }
  }
  stage('---compile---'){
    steps{
      sh "g++ -o hw hw.cpp"
    }
  }
  stage('---run---'){
    steps{
      sh "./hw"
    }
  }
}
