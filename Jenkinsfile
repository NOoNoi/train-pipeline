pipeline{
    agent any
    stages{
        stage("checkout"){
            /*when{
                expression{
                    return env.
                }
            }*/
            steps{
                checkout scm
                sh 'printenv'
            }
        }
    }
}