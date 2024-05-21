pipeline {
    agent any

    stages {
        stage("Delete data"){
            steps {
                deleteDir()
            }
        }
        stage("Create file"){
            steps {
                sh "touch File1"

            }
        }
        stage("adding data"){
            steps{
               echo "Build Number is : ${env.BUILD_NUMBER}"
            }
        }

    }
    
}