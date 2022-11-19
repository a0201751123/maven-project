pipeline {
    agent any
    stages {
    stage('maven install') {
      steps {
          withMaven(globalMavenSettingsConfig: 'null', jdk: 'JDK11', maven: 'Maven3', mavenSettingsConfig: 'null') {
      sh 'mvn clean install'
  }
      }
    }

  }

}
