pipeline{

    agent any

    stages{

        stage("Git Checkout"){

            steps{
                git branch: 'main', url: 'https://github.com/Emmylong1/My-Resume_Webapp.git'
            }
        }
                stage("Clean"){

            steps{
         
                sh 'mvn clean'
            }            
        }
    }
}
