pipeline{
    agent any
    tools { 
        maven 'Maven' 
        jdk 'java8' 
    }
    stages{
        stage('Build'){
            steps{
               echo 'done'
               bat 'java -version'
               bat 'cd c:\users\andres.cuartas\git\hw\my-app'
 			   bat 'mvn package'	
            }
        }
    }
}
