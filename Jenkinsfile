pipeline {
    agent any 
    stages {
        stage('Example Build') {
            steps {
               checkout scm
               echo 'Pulling...' + env.BRANCH_NAME
            }
        }
    }
}
