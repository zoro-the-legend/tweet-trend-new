pipeline {
    agent
    { 
    node {
        label 'slave'
    }
    }
        environment {
            PATH="/opt/maven/bin:$PATH"
        }
    stages {
        stage('Build') {
            steps {
               sh 'mvn clean install'
            }
        }
    }  
}
