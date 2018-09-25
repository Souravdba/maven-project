pipeline {
  agent any
  tools { 
        maven 'localMaven' 
        jdk 'localJDK' 
    }
  stages {
    stage('Compile') {
      steps {
         sh 'mvn clean compile'
    
    }
    }
    stage('Package Stage') {
      steps {
      
	 sh 'mvn clean package'
     

    }
  }
}
}
