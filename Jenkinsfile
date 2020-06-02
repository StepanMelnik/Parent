pipeline {
   agent any

   tools {
      maven "Maven3"
   }

   stages {
      stage('Build') {
         steps {
            git 'https://github.com/StepanMelnik/Parent.git'

            withMaven(globalMavenSettingsConfig: 'b08fcc34-34b9-4e53-ba93-898a88c8fb20', jdk: 'JDK8u221', maven: 'Maven3'){
                sh "mvn --version"
                sh "mvn clean deploy -X"
            }
         }
      }
   }
}
