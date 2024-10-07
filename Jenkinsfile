pipeline {
    agent any 

    stages {
        stage('git checkout'){
            steps{
                git branch: 'main', url: 'https://github.com/mtinyortaden/aws-cicd.git'
            }
        }
        stage('test'){
            steps{
                sh 'echo test'
            }
        }
    }
}