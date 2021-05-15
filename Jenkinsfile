node {
      withDockerRegistry(credentialsId: 'AP5Porky4us6q635uq3UtD85Xvj', url: 'http://vps-da3fb8c2.vps.ovh.ca:8082') {
        git credentialsId: '2775d8b3-f9a8-4ae9-a43e-279df01fa543', url: 'https://github.com/dutmond/Jenkinsfile.git'
        docker.build('myapp').push('latest')
    }    
}

/* 
pipeline {
    agent none
    stages {
        stage('build') {
            steps {
                withDockerRegistry(credentialsId: 'AP5Porky4us6q635uq3UtD85Xvj', url: 'http://vps-da3fb8c2.vps.ovh.ca:8082') {
                    git credentialsId: '2775d8b3-f9a8-4ae9-a43e-279df01fa543', url: 'https://github.com/dutmond/Jenkinsfile.git'
                    docker.build('myapp').push('latest')
                }    
            }
        }
    }
}
**/
