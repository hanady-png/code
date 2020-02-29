node {
     stage('SCM Checkout'){
   git 'https://github.com/hanady-png/code'
      }
      stage ('compile-package') {
           sh 'mvn clean verify'
      }
      }
