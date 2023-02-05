node{
  stage('Checkout from SCM'){
  git 'https://github.com/Rakeshdas3412/my_maven_app'
  }
  stage('Comlie-Package'){
    //Get maven home path
    def mvnHome = tool name: 'maven3', type: 'maven'
    sh ${mvnHome}/bin/'mvn package'
  }
  

}
