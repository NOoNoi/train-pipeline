pipeline{
    agent any
    stages{
        stage("checkout"){
            when{
                env.GIT_BRANCH == 'develop'
            }
            steps{
                //checkout scm
                git branch: 'develop',
                credentialsId: '112a46ce1ec8533bd5e7f97729792d6043',
                url: 'https://github.com/NOoNoi/train-pipeline.git'

                sh 'printenv'
            }
        }
    }
}