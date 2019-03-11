
pipeline {
  agent any
  tools {
    gradle 'SampleGradle'
    jdk 'JDK1.8'
  }
  stages {
    stage('Gradle Build') {
      steps {
        sh "gradle build"
      }
    }     
  }
}
   
