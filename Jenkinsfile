pipeline {
  agent any
  stages {
    stage ('codecheckout') {
      steps {
       git branch: 'master',  url: 'https://github.com/mamathabasavaiah/java-hello-world-webapp.git'
      }
    }
     stage("Build")
            steps {
             "mvn clean package"
             }
  }
}
