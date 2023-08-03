#!groovy

@Library('jenkinslib') _

def tools = new org.devops.tools()

pipeline{
    agent any
    stages{
        stage("demo"){
            step{
                tools.PrintMes("my first lib")
            }
        }
    }
}
