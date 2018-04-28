pipeline {
    agent {
        node {
           stages {
               stage(‘Deploy’) {
                   ansibleTower (
                       towerServer: ‘Tower-Prod’,
                       templateType: ‘job’,
                       jobTemplate: ‘myte1’,
                       importTowerLogs: ‘true’,
                       inventory: ‘myprod’
                   )
             }
         }
      }
   }  
}
