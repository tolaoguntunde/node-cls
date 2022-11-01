// pipeline {
//   agent any
    
//   tools {nodejs "node"}
    
//   stages {
        
//     stage('Git') {
//       steps {
//         git branch: 'main', credentialsId: 'ssh-git', url: 'https://github.com/tolaoguntunde/node-cls'
//       }
//     }
     
//     stage('Build') {
//       steps {
//         sh 'npm install'
//          //sh '<<Build Command>>'
//       }
//     }  
    
//   }
// }
pipeline {
  agent any
  tools {nodejs "node"}
  stages {
    stage("connect Git") {
      steps {
        sh 'git clone https://github.com/tolaoguntunde/node-cls.git'
        cd node-cls
      }
    }
    stage('build') {
      
    }
  }
  
}
