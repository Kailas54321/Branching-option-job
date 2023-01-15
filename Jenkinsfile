pipeline {
    agent any 
     stages {
        stage('code-checkout') { 
          steps { 
            sh ‘git branch -r | awk \'{print $1}\’ ORS=\’\\n\’ >branches.txt’
            
         }
       }
   } 
}
