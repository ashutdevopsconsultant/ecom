pipeline {
   agent any
   stages {
   stage('Preparation') { // for display purposes
      // Get some code from a GitHub repository
      //git 'https://github.com/AshutoshNI/ecom.git'
      // Get the Maven tool.
      // ** NOTE: This 'M3' Maven tool must be configured
      // **       in the global configuration.           
      
   }
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
