pipeline {
    agent any
    
          stages("codecheckout")
            {
             git branch: 'master',  url: 'https://github.com/mamathabasavaiah/java-hello-world-webapp.git'
            }
         stages("Build")
             {
             sh "${mavenHome}/bin/mvn clean package"
             }
        
    }

