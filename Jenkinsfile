node {
    stage('Git Checkout') { // for display purposes
     echo 'Checout Code and clone it inside jenkins workspace..'
     git 'https://github.com/Nasrin224/DeepriRepo.git'
   }
   stage('Build  & Package') {
      echo 'Build the package'
      sh 'mvn clean compile package'
   }
   stage('Test & Results') {
       echo 'Test Results are reported..'
      sh 'mvn test'
   }
   stage('Deploy to Dev'){
       echo 'Deploy to Dev environment'
   }
   stage('Deploy to Test'){
       echo 'Deploy to Test environment'
   }
      stage('Test Automation'){
       echo 'Deploy to Dev environment'
   }
   
}
