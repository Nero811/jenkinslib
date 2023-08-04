#!groovy

@Library('jenkinslib') _

def tools = new org.devops.tools()

pipeline{
    agent any
    stages{
        stage("demo"){
            steps{
                script{
                    tools.PrintMes("my first lib","red")
                    tools.PrintMes("my first lib","blue")
                    tools.PrintMes("my first lib","green")   
                    tools.PrintMes("my first lib","green1")
                }
            }
        }
    }
}
