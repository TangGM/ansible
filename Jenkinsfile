pipeline {
  agent none
  stages {
    stage('ansible') {
      steps {
        ansiblePlaybook(playbook: 'petclinic.yml', inventory: 'inventory', credentialsId: 'ssh-key', installation: 'ansible')
      }
    }

  }
}