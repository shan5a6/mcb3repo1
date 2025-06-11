pipeline {
  agent any
  parameters {
    choice choices: ['dev', 'prod'], name: 'ENV'
  }   
  environment {
    JAVA_HOME = "/opt/bin/java"
  }  
  stages {
    stage('working with variables ') {
      steps {
        script {
          var1=20
          println "my var1  value is ${var1}"
          println "BUILD_NO  is ${BUILD_NO}"
          println "WORKSPACE is ${WORKSPACE}"
          println "My selected ENV is ${params.ENV}"
          println "My JAVA HOME Path is ${env.JAVA_HOME}"
        }
      }
    }
  }
}
