pipeline {
    agent any 
    stages {
        stage('Example Build') {
            when { changeRequest() }
            steps {
               checkout scm
                echo 'Branch... ' + env.BRANCH_NAME
                echo 'Build number ...... ' +env.BUILD_NUMBER
                echo 'Build url....... '+env.BUILD_URL
                echo 'changeId..........' +env.CHANGE_ID
                echo 'i am in deploy'         
                echo sh(returnStdout: true, script: 'env')
            }
        }
    }
}
