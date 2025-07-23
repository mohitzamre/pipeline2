pipeline{
    agent any
    stages{
        stage('git checkout'){
            steps{
                checkout scm
		sh 'touch task1'
            }
        }
    }
}
