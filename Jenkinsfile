pipeline {
    agent any
      stages {
          stage('BrainTumorPredictionDeployment'){
                steps {
                    sh "sudo  cp -rvf * /root"
                    sh 'sudo ansible-paybook main.yml' 
                    
                }
        }
    }
}
