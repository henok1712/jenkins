pipeline{
agent any
stages {
    stage ('build Application'){
        steps {
        
            bat 'mvn clean install'
        }
    }
    stage ('Test Application'){
        steps{
        
            bat 'mvn clean test'
        }
    }
    stage('Deploy Application'){
        steps {
    
                   bat 'mvn clean package install deploy'
           
            }
        }
     }
 }