pipeline{
    agent any
    stages{
        stage("Git Checkut"){
            steps{
                script{
                    git branch: 'main', 
                    url: 'https://github.com/RahulAws2023/rahul_java_app.git'
                }
            }
        }
    }
}