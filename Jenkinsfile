pipeline {

    agent any
    
    stages {
        //  stage('build') {
        //   steps {
        //       bat 'npm install'
        //     }
        //   }
        
       stage('Build') {
            steps {
                bat 'docker build .'
                // Step to build Docker image
                // script {
                //     docker.build('Task:latest')
                // }
            }
        }
        
        // stage('Push') {
        //     steps {
        //         // Step to push Docker image to Docker registry
        //         script {
        //             docker.withRegistry('https://registry.hub.docker.com', 'jenkins-user-for-xyz-artifact-repository') {
        //                 docker.image('Task:latest').push('latest')
        //             }
        //         }
        //     }
        // }
        // stage('Deploy') {
        //     steps {
        //         // Step to deploy Docker image
        //         // You can use docker run command or deploy to a container orchestration platform like Kubernetes
        //         script {
        //             docker.image('Task:latest').run('-d -p 8080:80 --name my-container')
        //         }
        //     }
        // }

    }
}
