#!/usr/bin/env groovy


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


//pipeline {
//    agent none
//    stages {
//        stage('Run Tests') {
//            parallel {
//                stage('Test On Windows') {
//                    agent {
//                        label "windows"
//                    }
//                    steps {
//                        bat "run-tests.bat"
//                    }
//                    post {
//                        always {
//                            junit "**/TEST-*.xml"
//                        }
//                    }
//                }
//                stage('Test On Linux') {
//                    agent {
//                        label "linux"
//                    }
//                    steps {
//                        sh "run-tests.sh"
//                    }
//                    post {
//                        always {
//                            junit "**/TEST-*.xml"
//                        }
//                    }
//                }
//            }
//        }
//    }
//}