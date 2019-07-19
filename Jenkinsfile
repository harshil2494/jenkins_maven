pipeline {
  agent any 
    tools {
      jdk "Java-1.8"
      maven "Maven-3.5.3"
    }
  
  stages {
    stage ("clone git") {
      steps {
        git url: 'https://github.com/harshil2494/jenkins_maven.git'
      }
    }
      
  }
  
  
}
