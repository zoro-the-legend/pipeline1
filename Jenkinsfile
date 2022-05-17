node{
  stage('scm pull'){
   
    git 'https://github.com/Suraj177/hello-world-1'
  }
  stage('build'){
     def mvnHome = tool name: 'Maven', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
}
