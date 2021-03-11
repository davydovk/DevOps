pipeline {
    agent any
    
    environment {
        PROJECT_NAME = "Panda"
        OWNER_NAME = "Konstantin Davydov"
    }
    
    stages {
        stage('1-Build') {
            steps {
                echo 'Start of Stage Build'
                echo 'Building.......'
                echo 'End of Stage Build'
            }
        }
        stage("2-Test") {
            steps {
                echo 'Start of Stage Test'
                echo 'Testing.......'
                echo "Hello ${OWNER_NAME}"
                echo "Project name is ${PROJECT_NAME}"
                echo 'End of Stage Test'
            }
        }
        stage("3-Deploy") {
            steps {
                echo 'Start of Stage Deploy'
                echo 'Deploying.......'
                echo 'End of Stage Deploy'
            }
        }    
    }
}

