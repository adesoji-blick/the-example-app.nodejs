pipeline {
    agent any

    stages {
         stage ('stage one') {
             steps {
                echo 'building package'
		sh 'npm install'
             }
         }

         stage ('stage two') {
             steps  {
                 sh 'npm run start:dev &'
		 echo 'successfuly deployed'
             }
         }
        
        }
    }
  




