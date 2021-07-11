pipeline {
    agent any
      stages {
          stage('RunAnsiblePlaybook'){
                steps {
                    sh "sudo date"
                    sh "sudo  cp -rvf * /root"
                    sh "ansible-playbook   /root/main.yml" 
                    
                }
        }
    }
}
