pipeline{

        agent {
        label "master"
    }
        
        stages{

              stage('Quality Gate Status Check'){
                  steps{
                      script{
		    	    sh "echo mvn clean install"
                 	}

               	 }  
              }	
		
            }	       	     	         
}
