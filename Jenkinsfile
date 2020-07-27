pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                
                bat "mvn clean install"
            }
            
        }
        stage('test') {
            steps {
                
               echo "Test1"
            }
        
    }
}
