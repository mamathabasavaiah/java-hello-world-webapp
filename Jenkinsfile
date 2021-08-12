pipeline {
    agent any    
          stage("codecheckout")
            {
             git branch: 'master',  url: 'https://github.com/mamathabasavaiah/java-hello-world-webapp.git'
            }
         stage("Build")
             {
             sh "${mavenHome}/bin/mvn clean package"
             }
        
    }

