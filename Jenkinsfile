pipeline {
    agent any

    stages {
        stage('Get source code') {
            steps {
                sshagent(['demoAgent']) {
                        sh 'git clone git@github.com:vivekedulab/demo-jenkins.git'
                    }
            }
        }
    }
}
