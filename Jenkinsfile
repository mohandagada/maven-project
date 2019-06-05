node {
    stage('SCM Checkout'){
      git 'https://github.com/mohandagada/maven-project'
      }
      stage('compile-package'){
          def mvnHome = tool name: 'MAVEN_HOME=/root/softwares/maven3', type: 'maven'
      sh '$(mvnHome)/bin/mvn package'
      }
      }
