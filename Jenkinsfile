#!groovy
pipeline {
    agent none
   stages {     
    stage('Maven Install') {
      agent {         
       docker {          
         image 'swasthishekhar/project:tagname'         
     }       
  }       
  steps {
       sh 'docker run -p 8000:8000/tcp 68fd548b9c6b'
       }
     }
   }
 }