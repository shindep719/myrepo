pipeline {
    agent any
    environment {
        secret = credentials('prashant-aws-cred')
    }
    stages {
        stage('build') {
            steps {
               sh 'aws s3 cp index.html s3://codedeploydemobucket125'
            }
    
    }
 }
}
