pipeline{
agent
{
label "Slave_unix"
}
stages{
    stage("Testing"){
        steps{
            script{
                sh'/root/Scripts/test2.sh'
            }
        }
    }
}
}
