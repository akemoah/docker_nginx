pipeline{
agent build
  stages{
    stage("Déploiement Nginx avec docker") {
      step{
        ansiblePlaybook(
        colorized: true, 
        become: true,
        playbook: 'main.yml'
        )
      }
    }
  }
}
