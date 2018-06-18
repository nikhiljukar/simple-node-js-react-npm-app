pipeline {
     agent {
         docker {
             image 'node:6-alpine'
             args '-p 8085:8085'
         }
     }
     stages {
         stage('Build') {
             steps {
                 sh 'npm install'
             }
         }
     }
 }