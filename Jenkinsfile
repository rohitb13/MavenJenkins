pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'This is Building..
                sh '-B -DskipTests clean package'
            
                bat "mvn clean install"
            }
        }
        
    }
}
