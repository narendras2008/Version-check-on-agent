pipeline{
    agent{
        node{
            label"${Agent}"
        }
    }
    stages{
        stage('To check git version on agent'){
            steps{
                sh 'git --version'
            }
        }
        stage('To check java version on agent'){
            steps{
                sh 'java -version'
                        }
                    }
                  }
    post{
        always{
          cleanWs()
              }
    }
}
