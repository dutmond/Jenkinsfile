node {
    withDockerRegistry(credentialsId: 'AP5Porky4us6q635uq3UtD85Xvj', url: 'http://vps-da3fb8c2.vps.ovh.ca:8082') {
        git 'https://github.com/dutmond/Jenkinsfile.git'
    }    
}

/* 
pipeline {
    agent none
    stages {
        stage('build') {
            steps {
                withDockerRegistry(credentialsId: 'AP5Porky4us6q635uq3UtD85Xvj', url: 'http://vps-da3fb8c2.vps.ovh.ca:8082') {
                    git 'https://github.com/dutmond/Jenkinsfile.git'
                }    
            }
        }
    }
}
**/
