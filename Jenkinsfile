node {
   
   stage('SCM Checkout'){
	   
	git 'https://github.com/Reshwanth7/demo'
   
   }
   
    stage('Compile-Package'){
	   def mvnHome = tool name: 'Maven', type: 'maven'
	   
	   sh "${mvnHome}/bin/mvn package"
   }
}
