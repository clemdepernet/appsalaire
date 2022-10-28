 node{
      stage('Clone') {
          checkout scm
      }
      stage('Ansible') {
          ansiblePlaybook (
            inventory: 'inventaire',
            playbook: 'jenkinsplaybook.yml',
            colorized: true,
        )
      }
}
