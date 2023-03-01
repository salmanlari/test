pipeline{
  agent any
  stages{
    stage ("code checkout"){
      steps{
        sh 'echo "code check"' 
      }
    }
    stage ("create file"){
      steps{
        sh 'touch file1'
        sh 'echo "hello" > file1'
      }
    }
  }
}
