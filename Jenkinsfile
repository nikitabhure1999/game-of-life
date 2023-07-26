pipeline {
   agent {
              label "built-in"
                        }
    stages{
	      stage('deploy-index') {
			      steps {
                           sh "mvn clean"
						               sh "chmod -R 777 gameoflife.war"
                           sh "cp -r /mnt/gameoflife.war /mnt/apache-tomcat-9.0.76/webapps"
                           sh "./startup.sh"						   
					   
					   
					                }
			 
			 
			 
			 
			 }
	   
	   
	   
	   }
}
