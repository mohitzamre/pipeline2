pipeline{
    agent any
    stages{
        stage('git checkout'){
            steps{
                checkout scm
		bat 'touch task1'
            }
        }
    }
}
