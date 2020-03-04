pipeline {
    agent none
    
    stages {
        stage('Build') {
            agent {
                label 'xyz'
            }
            steps{
                echo "building....."
            }
            
        }
        stage('Test') {
            agent {
                label 'xyz'
            }
            steps {
                echo "Testing...."
            }
        }
        stage('deploy') {
            agent {
                label 'abc'
            }
            steps {
                echo "Deploying...."
            }
        }
    }
}
