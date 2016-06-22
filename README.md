# errai-tutorial-tomcat

Errai tutorial project that running on Tomcat server

Prerequisites
-------------

 * JDK 8 (run `java -version` on the command line to check)
 * Maven 3 (run `mvn --version` on the command line to check)
 
Install the original project
----------------------------

You must clone and install the original project on your local Maven repository

	% git clone https://github.com/errai/errai-tutorial
	
	% cd errai-tutorial
		
	% mvn install
	
Run on Tomcat
-------------

	% git clone https://github.com/stbland/errai-tutorial-tomcat.git
	
	% cd errai-tutorial-tomcat
	
	% mvn tomcat7:run-war
	
	% open http://localhost:8080/errai-tutorial/ in your web brower
	
