pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
              ansiblePlaybook(
        colorized: true, 
        become: true,
        playbook: 'main.yml',
        inventory: 'hosts'
        )
            }
        }
    }
}
