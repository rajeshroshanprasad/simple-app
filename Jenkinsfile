node{
    
}

pipeline{
    agent any 
    
    environment{
        PATH = "/opt/maven/bin:$PATH"
    }
    stages{
        stage ("git checkout"){
            steps{
                git 'https://github.com/rajeshroshanprasad/hello-world.git'
            }
        }
        stage("maven build"){
            steps{
                sh "mvn clean package"
            }
            
        
        }
    
    }
    
}
