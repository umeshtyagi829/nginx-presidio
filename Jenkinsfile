pipeline {
    agent any
      stages {
          stage('RunAnsiblePlaybook'){
                steps {
                    sh "sudo date"
                    sh "sudo  cp -rvf * /home/ec2-user"
                    sh "sudo ansible-playbook   /home/ec2-user/main.yml" 
                    
                }
        }
    }
}
