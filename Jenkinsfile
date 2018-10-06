node {
   def mvnHome
   stage('Preparation') { // for display purposes
      // Get some code from a GitHub repository
      //git 'https://github.com/jglick/simple-maven-project-with-tests.git'
        git 'https://github.com/vinaykumarhebballi123/gitbox.git'
   }
   stage('Build') {
       bat '''
       echo "building!!!!!!!!!!!! "
       call C:/vinay/test.bat stop
       EXIT /B 0
       '''
   }
   stage('Results') {
       echo "results.........."
       
       build job: 
   }
}
