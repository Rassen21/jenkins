pipeline {
   agent {
       node {
           stage(‘Deploy’) {
               ansibleTower (
                   towerServer: ‘Tower-Prod’,
                   templateType: ‘job’,
                   jobTemplate: ‘none’,
                   importTowerLogs: ‘true’,
                   inventory: ‘myprod’
               )
           }
       }
   }
}
