pipeline{
    agent{
        node{
            label 'maven'
        }
    }
    stages {
        stage('build job'){
            steps{
                git branch:'main', url:'https://github.com/Shakil16/twitt-trend.git'
            }
        }
        
    }
}
