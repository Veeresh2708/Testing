pipeline{
agent
{
label "Slave_unix"
}
stages{
    stage("Testing"){
        steps{
            script{
                sh 'ls -lrt /root/Scripts'
                sh '/root/Scripts/web.sh'
            }
        }
    }
}
}
