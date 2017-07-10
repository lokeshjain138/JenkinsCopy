node {
   // Mark the code checkout 'stage'....
   stage 'Checkout'
   
   git url: 'https://github.com/lokeshjain138/JenkinsCopy.git'

   // Get the maven tool.
   // ** NOTE: This 'M3' maven tool must be configured
   // **       in the global configuration.           
   def mvnHome = tool 'M3'

   // Mark the code build 'stage'....
   stage 'CopyingFiles'
   // Run the maven build
 // sh "${mvnHome}/bin mvn -Dmaven.test.failure.ignore clean package"
   //run command
   //C:\\Program Files (x86)\\Jenkins\\workspace\\JenkinsCopy\\README.md
  // echo ${JENKINS_HOME}
//   shell "${JENKINS_HOME}/workspace/JenkinsCopy Copy README.md D:/AWS"
    bat "Copy C:/Program Files (x86)/Jenkins/workspace/JenkinsCopy/README.md D:/AWS"
//bat "mvn -Dmaven.test.failure.ignore clean package"
   echo "Done"
   //step([$class: 'JUnitResultArchiver', testResults: '**/target/surefire-reports/TEST-*.xml'])
}
