node{

  def mvnPath = tool name: 'maven3', type: 'maven'
  
  stage('SCM Checkout')
  {
     
     git 'https://github.com/druvsingh42/my-app-1'
     echo 'checkout1234567890'
     
    sh "${mvnPath}/bin/mvn clean"
    
  }
  
    stage('Compile Package')
  {
    
    
   echo 'compile1234567890'
   sh "${mvnPath}/bin/mvn install"
    
  }


}
