pipeline { 
  
  agent any

  tools {
        nodejs 'NODEJS' // Name of the Node.js configuration in Jenkins
  }
  
  stages {
     stage('Install Dependencies') { 
        steps { 
           bat 'npm install' 
        }
     }
     
     stage('Test') { 
        steps { 
           bat 'echo "testing application..."'
        }
     }
  
  }
}
