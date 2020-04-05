pipeline {
    agent any
    stages {
         stage ('First stage') {
             steps {
                 echo "Running code package"
                 sh 'npm install'
             }
         }
         stage ('Second stage') {
             steps {
                 echo "Deploying code"
                 sh 'npm run start:dev &'
                 echo "Successfully deployed"
             }
         }

    }
}
