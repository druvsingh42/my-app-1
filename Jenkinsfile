node{

  def mvnPath = tool name: 'maven3', type: 'maven'
  
  stage('SCM Checkout')
  {
     def mvnPath = tool name: 'maven3', type: 'maven'
     git 'https://github.com/druvsingh42/my-app-1'
     echo 'checkout1234567890'
     
    sh "${mvnPath}/bin/mvn clean"
    
  }
  
    stage('Compile Package')
  {
    
   def mvnPath = tool name: 'maven3', type: 'maven' 
   echo 'compile1234567890'
   sh "${mvnPath}/bin/mvn install"
    
  }


}
