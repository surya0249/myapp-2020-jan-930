node('master'){
    
     env.PATH = "/opt/maven3/bin/:$PATH"
    stage('build'){
        sh "mvn clean package"
     }
    
}
