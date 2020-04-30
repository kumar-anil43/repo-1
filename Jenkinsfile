node{
  stage('SCM Checkout') {
    git 'https://github.com/kumar-anil43/repo-1'
    }
    stage('Compile-Package'){
      // Get maven home path
      def mvnHOME = tool name: 'M2_HOME', type: 'maven'
      sh "${mvnHOME}/bin/mvn package"
     }
     
     }
