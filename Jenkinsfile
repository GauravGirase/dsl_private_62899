pipeline {
    agent any
    stages {
        stage ('Git Clone') {
            steps {
                git url: "git@github.com:GauravGirase/private_repo_62899.git", branch: "main",
                credentialsId: "ssh_62899"
            }
            
        }
    }
}
