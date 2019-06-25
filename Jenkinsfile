pipeline {
    agent any 
    stages {
        stage('Example Build') {
            steps {
               echo 'Pulling...' + env.BRANCH_NAME
               checkout scm
            }
        }
    }
}
