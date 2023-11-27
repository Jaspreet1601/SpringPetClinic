pipeline{
    agent any 
    tools{maven'm1'}
        stages{
                stage("Fetching"){
                    steps{git branch:'main',url:'https://github.com/Jaspreet1601/SpringPetClinic.git'}}
                        
                stage ("compile"){
                    steps{bat 'mvn compile'}}
                    
                stage ("test"){
                    steps{bat 'mvn test'}}
                    
                stage ("Package"){
                    steps{bat 'mvn package'}}
                
                stage ("Verify"){
                    steps{bat 'mvn verify'}}
                    
                stage ("Install"){
                    steps{bat 'mvn install'}}
            
            }
        }
