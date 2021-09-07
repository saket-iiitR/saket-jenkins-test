pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') { 
            steps { 
                echo 'Build'
                echo 'Testing POLL SCM'
            }
        }
        stage('Test'){
            steps {
                echo 'Test'
            }
        }
        stage('Deploy') {
            steps {
                 echo 'Deploy'
            }
        }
    }
}
