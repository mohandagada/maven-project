node{
    stage('SCM Checkout'){
     git  'https://github.com/mohandagada/maven-project.git'
    }
     stage('Compile-Package')
     {
    def mvnHome = tool name: 'MAVEN_HOME=/root/softwares/maven3', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
}
}  
