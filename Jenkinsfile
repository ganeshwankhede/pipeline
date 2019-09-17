node {
   //def mvn = tool (name: 'maven3', type: 'maven') + '/bin/mvn'
   stage('SCM Checkout'){
    // Clone repo
    	git branch: 'master', 
	    credentialsId: 'github', 
	    url: 'https://github.com/javahometech/myweb'
   }
   
   stage('echo_msg'){
      echo "checkout"	     
   }
}
