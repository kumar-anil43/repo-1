node{
  stage('SCM Checkout') {
    git 'https://github.com/kumar-anil43/repo-1'
    }
       stage("Maven Clean package"){
        def mavenHome= tool name: "M2_HOME", type: "maven"
        def mavenCMD= "${MavenHome}/bin/mvn"
        sh "${mavenCMD} clean package"

     }
     
     }
