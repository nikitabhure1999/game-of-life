pipeline {
   agent {
              label "built-in"
                        }
    stages{
	      stage('deploy-index') {
			      steps {
		           sh "git clone 		      
			   sh "mvn install"	      
                           sh "mvn clean"
		           sh "cp -r  target/gameoflife.war /mnt/game-of-life/game-of-life-web 		      
			   sh "chmod -R 777 gameoflife.war"	      
                           sh "./startup.sh"						   
					   
					   
					                }
			 
			 
			 
			 
			 }
	   
	   
	   
	   }
}
