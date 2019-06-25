pipeline {
    agent any 
    stages {
        stage('Example Build') {
            when { changeRequest() }
            steps {
               echo 'Pulling...' + env.BRANCH_NAME
               echo 'Building...' + env.CHANGE_ID
               checkout scm
            }
        }
    }
}
