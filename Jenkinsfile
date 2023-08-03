#!groovy

@Library('jenkinslib') _

def tools = new org.devops.tools()

pipeline{
    agent any
    stages{
        stage("demo"){
            steps{
                script{
                    tools.PrintMes("my first lib")   
                }
            }
        }
    }
}
