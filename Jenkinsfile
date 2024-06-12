pipeline  {
    agent {
        label 'AGENT-1'
    }

    options {
        timeout(time:1, unit:'seconds')
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh sleep 10
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}