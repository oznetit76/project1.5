pipeline{
  agent any
  stage('maven install') {
  steps {
   withMaven(globalMavenSettingsConfig: 'null', jdk: 'null', maven: 'null', mavenSettingsConfig: 'null') {
    sh 'mvn clean install'
      }
    }
  }
}
