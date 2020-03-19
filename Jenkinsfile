pipeline {
    agent any 
    stages {
        stage('clone project') { 
            steps {
                sh "mvn clean"
            }
        }
        stage('test project') { 
            steps {
                sh "mvn test " 
            }
        }
        stage('deploye') { 
            steps {
                sh "mvn package"
            }
        }
    }
}
