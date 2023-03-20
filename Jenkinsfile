pipeline {
    agent any

    stages{
        stage("create zip file"){
            steps{

                sh 'zip middlewarescript-${BUILD_NUMBER}.ZIP * --exclude Jenkinsfile README.md'
                
            }
        }
    }
}