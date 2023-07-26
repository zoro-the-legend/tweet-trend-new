pipeline {
    agent
    { 
    node {
        label 'slave'
    }
    }

    stages {
        stage('Git clone') {
            steps {
                git branch: 'main', url: 'https://github.com/zoro-the-legend/tweet-trend-new.git'
            }
        }
    }
}