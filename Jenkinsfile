node {
  stage ('Run Ansible'){
  def mvnHome = ansiblePlaybook become: true, credentialsId: 'ansadm', installation: 'MyAnsible', inventory: 'hosts', playbook: 'first.yml'
  sh "${mvnHome}"
  }
}


