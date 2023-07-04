pipeline{
    agent any
    stages {
        stage("clone code"){
           steps{
              git url: 'https://github.com/spring-projects/spring-petclinic.git' 
               
           }    
            
            
        }
        stage("Build code"){
           steps{
              sh "mvn clean package" 
               
           }    
            
        }
        
        
        
        
    }
    
    
    
    
    
    
    
    
    
}
