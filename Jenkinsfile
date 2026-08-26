pipeline {
    agent any
    stages {
<<<<<<< HEA
=======
        stage ('buildSatge'){
>>>>>>> e626671d0150cceb45aa99366a038f38efafa370
            steps {
<<<<<<< HEAD
                echo "building the code "
=======
                echo "building the  application:"
>>>>>>> e626671d0150cceb45aa99366a038f38efafa370
            }
        }
        stage ('test'){
            steps {
                echo "test the code quality"
            }
        }
        stage ('scan'){
            steps {
                echo "scanning the code quality"
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

