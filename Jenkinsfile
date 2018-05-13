//Jenkinsfile (Declarative Pipeline)
//pipeline {
//    agent any 
//    stages {
//        stage('Build') { 
//            steps {
//                echo("hello jenkins Build") 
//            }
//        }
//        stage('Test') { 
//            steps {
//                //
//                echo("hello jenkins from") 				
//            }
//        }
//        stage('Deploy') { 
//            steps {
//                // 
//                echo("hello jenkins from Deploy") 
//            }
//        }
//    }


pipeline {
   agent none
   stages {
       stage("first") {
           def foo = "foo" // fails with "WorkflowScript: 5: Expected a step @ line 5, column 13."
           sh "echo ${foo}"
       }
   }
}