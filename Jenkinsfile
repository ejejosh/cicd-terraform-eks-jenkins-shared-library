@Library('my-shared-library') _ 

pipeline{

    agent any

    stages{
         
        stage('Git Checkout'){
            steps{
                gitCheckout(
                    branch: "main",
                    url: "https://github.com/ejejosh/cicd-terraform-eks-jenkins-shared-library.git"
                )
            }
        }     
    }
}