pipeline{
agent{
    Slave_unix
    }
stages{
    Stage(Testing){
        steps{
            script{
                sh'test2.sh'
            }
        }
    }
}
}