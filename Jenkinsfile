pipeline {
   agent any
   stages {
   
   stage('Clean') {
   steps { 
   withMaven(maven : 'maven_3_5_0'){
   sh 'mvn clean'
   }
   
   }
      
   }
   
   stage('Install') {
   steps { 
   withMaven(maven : 'maven_3_5_0'){
   sh 'mvn clean install'
   }
   
   }
      
   }
   
  
}
}
