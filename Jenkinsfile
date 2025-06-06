pipeline {
    agent {
        docker {
            image 'roemer/universal-jenkins-agent:latest'
        }
    }
    stages {
        stage('Build') {
            steps {
                echo "Building from branch ${env.BRANCH_NAME}"
            }
        }
    }
}
