pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('compile') {
            steps {                                
                   cmd 'mvn clean compile'            
            }
        }
    }
}
