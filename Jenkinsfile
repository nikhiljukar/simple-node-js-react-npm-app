pipeline {
     agent {
         docker {
             image 'node:6-alpine'
             args '-p 8084:8084'
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