pipeline {
    agent any 
    stages {
        stage('Checkout') {
            steps {
                script {
                    // Checkout your source code from the repository.
                    checkout([
                        $class: 'GitSCM',
                        branches: [[name: '*/master']], 
                       userRemoteConfigs: [[url: 'https://github.com/salimsghaier7/Devops.git']]
                    ])
                }
            } 
        }
    }
}
