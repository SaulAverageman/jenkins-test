pipeline{
    agent any
    stages{
        stage("any"){
            steps{
                script{
                    prop= readProperties file "setup k8s cluster.txt"
                    println prop
                }
            }
        }
    }
}