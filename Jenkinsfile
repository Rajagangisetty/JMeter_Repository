pipeline {

	agent any
  
  stages {
   
    stage('Execute Jmeter') {

	    
	    steps {
              bat("dir")
              bat("jmeter -n -t sample.jmx -l 1.jtl")
      	}
      	
    }
  }
}
