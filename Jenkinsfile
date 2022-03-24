pipeline {
    agent any
    stages {
        stage('devops') {
            parallel {
                stage('Test On stage 1') {
                    
                    steps {
                        sh "echo stage 1"
                    }
                    
                }
                stage('Test On stage 2') {
                    
                    steps {
                        sh "echo stage 2"
                    }
                   
                }
            }
        }
        }
}
