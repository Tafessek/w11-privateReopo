# w11-privateReopo
Access private repo from jenkins
node('linux'){
   stage('Test'){
      git credentialsId: '18104abb-c394-4852-9510-3999fcb30c69', url: 'https://github.com/rclc/W11-PrivateRepo.git'      
   }
}
