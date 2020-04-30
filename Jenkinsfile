pipeline {
    agent any
    tools {
        maven 'maven3'
    }
    stages{
      
        stage('build'){
            sh script : 'mvn clean package'
        }
    }
}
