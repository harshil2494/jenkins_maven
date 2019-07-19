pipeline {
  agent any 
    tools {
      jdk "myjava"
      maven "mymaven"
    }
  
  stages {
    stage ("clone git") {
      steps {
        git url: 'https://github.com/harshil2494/jenkins_maven.git'
        sh 'mvn -version'
      }
    }
      
  }
  
  
}
