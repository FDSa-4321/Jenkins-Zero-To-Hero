pipeline{
    agent any
    stages{
      
      stage('Git Checkout'){
            steps{
                echo 'This is a Git Checkout Stage'
                #git branch: 'main', credentialsId: 'Git-Credentials', url: 'https://github.com/FDSa-4321/Jenkins-Zero-To-Hero.git'
            }
        }
        
      stage('Build'){
            steps{
                echo 'This is a Build Stage'
            }
        } 
        
      stage('Test'){
            steps{
                echo 'This is a Test Stage'
            }
        }
        
      stage('Deploy'){
            steps{
                echo 'This is a Deploy Stage'
            }
        }
        
    }
}
