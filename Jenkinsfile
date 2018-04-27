pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'mvn clean package'
        echo 'Build done'
      }
    }
    stage('Test') {
      steps {
        bat 'echo " Testting done"'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deployment done'
      }
    }
  }
  environment {
    JAVA_HOME = 'C:\\Program Files\\java\\jdk1.8.0_144'
    MAVEN_HOME = 'F:\\apache-maven-3.5.2'
  }
}