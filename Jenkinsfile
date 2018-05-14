#!/usr/bin/env groovy

pipeline {
   environment {
     FOO = "foo"
   }

   agent any
   stages {
       stage('first') {
           //sh "echo ${FOO}"
		   stage("WS Cleanup") {
		   echo("hello world")
		   }
       }
   }
}