pipeline {
    agent any 

    stages {
        stage('Build') {
            steps {
          
                echo 'Building Docker Images'
                echo 'npm install ....'
                echo 'building ddependencies'  
            }
        }
        stage('Test'){
            steps {
                
                echo 'Running Tests'
                echo 'Tests are Successfully executed'
            }
        }
        stage('Deploy'){
            steps {
                echo 'Deploying the APP ....'
            }
        }
    }
}
