pipeline{
agent
{
label "Slave_unix"
}
stages{
    stage("Testing"){
        steps{
            script{
                sh'test2.sh'
            }
        }
    }
}
}
