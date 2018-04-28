pipeline {
    agent {
        node {
           stages {
               stage(‘Deploy’) {
                   ansibleTower (
                       towerServer: ‘Tower-Prod’,
                       templateType: ‘job’,
                       jobTemplate: ‘mytemplate’,
                       importTowerLogs: ‘true’,
                       inventory: ‘myprod’
                   )
             }
         }
      }
   }  
}
