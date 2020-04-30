pipeline {
    agent any
    tools {
        maven 'maven3'
    }
    stage('build'){
        sh script : 'mvn clean package'
    }
}
