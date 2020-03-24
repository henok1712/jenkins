pipeline{
  agent any
  stages {
    stage ('build Application'){
        steps {
        
            bat 'mvn clean install'
        }
    
    }
    stage('Deploy Application Mulesoft Cloudhub'){
        steps {
    
                   bat 'mvn package deploy -DmuleDeploy '
            }
        }
     }
 }