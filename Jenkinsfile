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
               bat 'mvn clean'	
            }
        }
    }
}
