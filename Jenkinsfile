pipeline {
  agent any 
  stages {
    stage('working with loops') {
      steps {
        script {
          for(i=1;i<=5;i++) {
            println "my i value is ${i}"
          }
          mylist1=["devops","azure","aws"]
          for(item in mylist1) {
            println "my ele is ${item}"
          }
          j=10
          while(j<=15) {
            println "my j value is ${j}"
            j = j + 1 
          }
        }
      }
    }
  }
}

