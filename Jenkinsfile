node{
  stage('SCM Checkout'){
    git 'https://github.com/Sidharth4082/mavenwebapp.git'
  }
  stage('Comile-Package'){
    def mvnHome = tool name: 'maven-3', type:'maven'
    sh "${mvnHome}/bin/mvn package"
  }
}
