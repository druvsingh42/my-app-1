node{

  
  
  stage('SCM Checkout')
  {
     def mvnPath = tool name: 'maven3', type: 'maven'
     git 'https://github.com/druvsingh42/my-app-1'
     echo 'checkout1234567890'
    echo "${mvnPath}"
    sh "${mvnPath}/bin/mvn build"
    
    echo 'checkout111111111'
    
  }
  
    stage('Compile Package')
  {
    
  
   echo 'compile1234567890'
   sh "${mvnPath}/bin/mvn install"
   echo 'compile222222222' 
  }


}
