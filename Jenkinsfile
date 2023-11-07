pipeline {
    agent any
    
        environment {
            PATH="/opt/maven/bin:$PATH"
        }
    stages {
        stage('Build') {
            steps { 
               sh 'https://github.com/zoro-the-legend/hello-world-1.git mvn clean install'
            }
        }
    }  
}
