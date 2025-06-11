def mycode(a=20,b=30){
  sum = a + b 
  println "welcome to functions & sum is ${sum} "
}

pipeline {
  agent any 
  stages {
    stage('welcome note') {
      steps {
        script {
          mycode()
          mycode(100,200)
        }
      }
    }
  }
}
