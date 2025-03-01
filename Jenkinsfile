pipeline {
    agent any
    tools{
        maven 'Maven Apache'
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}