node {
     stage('SCM Checkout'){
   git 'https://github.com/hanady-png/code'
      }
      stage ('compile-package') {
      def mvn = tool (name: 'maven3', type: 'maven') 
      sh "${mvnHome}/bin/mvn"
      }
      }
