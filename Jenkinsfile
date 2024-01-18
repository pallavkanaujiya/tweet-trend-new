pipeline {
    agent{
        node{
            label "maven"
        }
    }

    stages {
        stage('Git clone') {
            steps {
                git branch: 'main', url: 'https://github.com/pallavkanaujiya/tweet-trend-new.git'
            }
        }
    }
}
