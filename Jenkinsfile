pipeline {
    agent any
}
   stages {
        stage('Git Checkout') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/bloomytech/samplemaven.git']]])
            }
        }
   }
}
