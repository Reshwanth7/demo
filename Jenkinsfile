node {
   
   stage('SCM Checkout'){
	git branch: 'master', 
	
	url: 'https://github.com/Reshwanth7/demo'
   
   }
   
    stage('Mvn Package'){
	   // Build using maven
	   
	   sh "${mvn} clean package deploy"
   }
}
