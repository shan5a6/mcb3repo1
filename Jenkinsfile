pipeline {
  agent any 
  stages {
    stage('welcome note') {
      steps {
        script {
          File file = new File("/opt/mydata.txt")
          def lines = file.readLines()
          println "Lines\n ${lines}"
          for (line in lines) {
            println "myline is ${line}"
          }
        }
      }
    }
  }
}
