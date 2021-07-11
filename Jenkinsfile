pipeline {
    agent any
      stages {
          stage('RunAnsiblePlaybook'){
                steps {
                    sh "sudo date"
                    sh "sudo  cp -rvf * /home/ec2-user"
                  //  sh "/usr/bin/ansible-playbook -i   /home/ec2-user/main.yml"
                    sh "sudo /usr/local/bin/ansible-playbook    /root/a.yml" 
                    
                }
        }
    }
}
