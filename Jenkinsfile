pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
              ansiblePlaybook(
        colorized: true,
        sudo: true,
        //become: true,
        playbook: 'main.yml',
        inventory: 'hosts.ini'
        )
            }
        }
    }
}
