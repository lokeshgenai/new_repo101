pipeline {
    agent any 
    stages {
        stage('Checkout') {
            steps{
                echo 'Checking out the code grom Github...'
            }
        }
        stage("Build and Test") {
            steps {
                echo "Executing build stepson the Centos VM..."
                sh 'uname -a'
                sh 'uptime'
            }
        }
    }


}
