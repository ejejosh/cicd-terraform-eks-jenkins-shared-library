pipeline{

    agent any

    stages{
         
        stage('Git Checkout'){
            steps{
                script{
                    git branch: 'main', url: 'https://github.com/ejejosh/cicd-terraform-eks-jenkins-shared-library.git'
                }
            }
        }     
    }
}