pipeline {
  agent any
    
  tools {nodejs "node"}
    
  stages {
        
    stage('Git') {
      steps {
        sh 'git branch: "main", credentialsId: "ssh-git", url: https://github.com/tolaoguntunde/node-cls.git'
      }
    }
     
//     stage('Build') {
//       steps {
//         sh 'npm install'
//          //sh '<<Build Command>>'
//       }
//     }  
    
            
//     stage('Test') {
//       steps {
//         sh 'node test'
//       }
//     }
  }
}
