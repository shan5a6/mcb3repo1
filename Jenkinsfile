def mycode(a,b){
  sum = a + b 
  println "welcome to functions & sum is ${sum} "
}

pipeline {
  agent any 
  stages {
    stage('welcome note') {
      steps {
        script {
          mycode(10,20)
        }
      }
    }
  }
}
