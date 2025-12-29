pipeline{
    agent{
        label'java-slave'
    }

    environment{
        // key = value
        course = "Kubernetes"
        name = "Dinesh"
    }

    stages{
        stage('Build'){
            steps{
                echo"*** This is a building stage *****"
                echo"***** Welcome to ${name}"
                echo"***** Welcome to ${course}, All the Best ${name}"
            }
            
        }
    }
}

    
