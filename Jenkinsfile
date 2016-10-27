node {
   stage 'checkout'
   svm checkout
   
   stage 'build'
   def mvn = tool 'maven3'
   sh "${mvn}/bin/mvn test
}
