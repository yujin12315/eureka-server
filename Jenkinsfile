pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'sh \'mvn -B -DskipTests clean package\''
      }
    }

    stage('test') {
      steps {
        sh 'echo \'test\''
      }
    }

  }
}