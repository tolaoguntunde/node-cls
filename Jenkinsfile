pipeline {
  agent any
    
  tools {nodejs "node"}
    
  stages {
        
    stage('Git') {
      steps {
        sh 'git clone https://github.com/tolaoguntunde/node-cls.git'
        sh'cd node-cls'
      }
    }
     
    stage('Build') {
      steps {
        sh 'npm install'
         //sh '<<Build Command>>'
      }
    }  
    
            
    stage('Test') {
      steps {
        sh 'node test'
      }
    }
  }
}
