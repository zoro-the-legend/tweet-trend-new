pipeline {
    agent
    { 
    node {
        label 'slave'
    }
    }
        enviroment {
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