pipeline{
    agent none
    stages {
            stage('Java Tasks') {
                agent {
                    label 'test'
                }
                stages {
                    stage('Generate Code') {
                        steps {
                            sh 'echo 1'
                        }
                    }
                }
            }
    }
}