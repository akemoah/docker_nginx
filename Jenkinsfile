pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
              ansiblePlaybook(
        colorized: true, 
        become: true,
        inventory: hosts,
        playbook: 'main.yml'
        )
            }
        }
    }
}
