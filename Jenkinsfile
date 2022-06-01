pipeline {
    agent any
stages {

               
         stage('Build-Step') {
             when {
               branch 'PR-1'                  
             }
             steps {
                     echo 'Build Step '
             }
         }
     

        stage('Change-Step') {
              steps {
                   echo 'Change Step'
                   snDevOpsChange()
              }
        }
}
   
}
