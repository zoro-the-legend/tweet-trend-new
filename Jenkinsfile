pipeline {
    agent any
    
        environment {
            PATH="/opt/maven/bin:$PATH"
        }
    stages {
        stage('Build') {
            steps { 
               sh '/opt/maven/bin/mvn clean install'
            }
        }
    }  
}
