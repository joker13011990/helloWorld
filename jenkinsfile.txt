Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo("hello jenkins Build") 
            }
        }
        stage('Test') { 
            steps {
                //
                echo("hello jenkins from") 				
            }
        }
        stage('Deploy') { 
            steps {
                // 
                echo("hello jenkins from Deploy") 
            }
        }
    }
}