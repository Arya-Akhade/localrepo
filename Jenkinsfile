pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
               git branch: 'main', credentialsId: '1ae27261-837a-4b98-a17b-6febdd199589', url: 'https://github.com/Arya-Akhade/localrepo.git'
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
