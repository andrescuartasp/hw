pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
               echo 'done'
               sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
