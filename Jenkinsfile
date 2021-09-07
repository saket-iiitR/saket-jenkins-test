pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') { 
            steps { 
                echo 'Build'
            }
        }
        stage('Test'){
            steps {
                sh 'Test'
            }
        }
        stage('Deploy') {
            steps {
                sh 'Deploy'
            }
        }
    }
}
