pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                echo 'Hello world'
            }
        }    
         stage('complie') {
            steps {
                bat "javac jenkinsfile.java"
            }
         }
         stage('run') {
            steps {
                bat "java jenkinsfile"
            }
         }
         
        
    }
}
