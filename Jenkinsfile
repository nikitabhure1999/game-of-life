pipeline {
   agent {
              label { 
		      label "built-in"
        	      customWorkspace "/mnt/data"
	      } 
                        }
    stages{
	      stage('deploy-game-of-life war'){
			      steps {                         
				                       
				                  sh "cd /mnt/dat git clone https://github.com/nikitabhure1999/game-of-life.git"
                                                   sh "mvn clean "
				                   sh "mvn install"
                                                   sh "cp -r  /mnt/data/game-of-life/game-of-life-web/target/gameoflife.war /mnt/servers/apache-tomcat-9.0.78/webapps"
						   sh "chmod -R 777/mnt/servers/apache-tomcat-9.0.78/webapps"
                          					   
					   
					   
					                }
			 
			 
			 
			 
			 }
	   
	   
	   
	   }
}
