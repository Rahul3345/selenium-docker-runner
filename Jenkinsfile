pipeline{

    agent any

    stages{
    stage('Run Tests')
    {
        steps{
             bat "docker-compose up"
                }
    }
    stage('Docker close')
    {
         steps{
               bat "docker-compose down"
                }
    }
        }
   }