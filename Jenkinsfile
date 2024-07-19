pipeline {
    agent any

    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }

        stage('Build'){

            steps{

                echo "Test"
            }
        }
    }

    post {
        
        always{
            echo 'Pipeline status is completed' 
        }

        success{
            echo 'Pipeline status is success'
        }
        failure{
            echo 'Pipeline status is failure'
        }
    }
}