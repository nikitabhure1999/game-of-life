pipeline {
   agent {
              label "built-in"
                        }
    stages{
	      stage('deploy-game-of-life war'){
			      steps {                         
				                       
				
                                                   sh "mvn clean install"
                                                   sh "cp -r gameoflife.war  /mnt/servers/apache-tomcat-9.0.78/webapps"
						   sh "chmod -R 777/mnt/servers/apache-tomcat-9.0.78/webapps"
                          					   
					   
					   
					                }
			 
			 
			 
			 
			 }
	   
	   
	   
	   }
}
