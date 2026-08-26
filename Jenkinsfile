pipeline {
    agent any
    stages {
        stage ('buildSatge'){
            steps {
                echo "building the  application:"
            }
        }
        stage ('test'){
            steps {
                echo "test the application quality"
            }
        }
        stage ('scan'){
            steps {
                echo "scanning the application quality"
            }
        }
        stage ('nexus'){
            steps {
                echo "store the artifactory"
            }
        }
        stage ('dockerfile'){
            steps {
                echo "create the image"
            }
        }
        stage ('hub'){
            steps {
                echo "store the image in hub"
            }
        }
        stage ('dev'){
            steps {
                echo "deploy the image into dev"
            }
        }
        stage ('stage'){
            steps {
                echo "dev to stage"
            }
        }
        stage ('pro2'){
            steps {
                echo "stage to prod2"
            }
        }
        stage ('prod1'){
            steps {
                echo "prod2 to pro1"
            }
        }
    }
}

