@Library('MyLibrary') _
pipeline {
    agent any
    stages {
        
        stage('Hello World') {
            steps {
                script 
                {
                    hello.hello()
                }
            }
        }
        
        stage('Checkout code from Git') {
            steps {
                script 
                {
                    checkout_git.checkout_git()
                }
            }
        }
        stage('codebuild trigger') {
            steps {
                script 
                {
                    codebuild.codebuild()
        
                }
    
               }
           
              }
    }
}