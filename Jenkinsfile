pipeline {
    agent any
    stages {
    stage('maven install') {
      steps {
          withMaven(globalMavenSettingsConfig: 'null', jdk: 'JDK11', maven: 'null', mavenSettingsConfig: 'null') {
      sh 'mvn clean install'
  }
      }
    }

  }

}
