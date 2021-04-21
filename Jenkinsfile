pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
        stage('Scripting') {
            steps {
                script{
                    if (2+2!=4) { 
         //If the condition is true print the following statement 
         println("uuuuu"); 
      } else { 
         //If the condition is false print the following statement 
         println("jeeeeej"); 
      } 
                }
            }
        }
    }
}
