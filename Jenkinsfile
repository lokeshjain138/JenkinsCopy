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
   sh cp "C:\\Program Files (x86)\\Jenkins\\workspace\\jenkins_pipeline_java_maven_\\README.md" "D:\\AWS"
   //step([$class: 'JUnitResultArchiver', testResults: '**/target/surefire-reports/TEST-*.xml'])
}
