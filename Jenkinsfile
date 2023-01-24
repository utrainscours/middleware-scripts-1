pipeline {
    agent any

    stages{
        stage("create zip file"){
            steps{
             sh 'zip middlewarescript.zip-$(date +%y%m%d-%H%M%S) * --exclude Jenkinsfile  README.md'
            }
        }
            
    }
}