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
               mvn clean
               mvn compile
            }
        }
    }
}
