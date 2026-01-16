pipeline {
    agent {
        node {
            label 'built-in'
        }
    }

    stages {
        stage('RUN CHECK') {
            steps {
                echo "Running on node: ${env.NODE_NAME}"
                echo "Workspace: ${env.WORKSPACE}"
            }
        }
    }
}
