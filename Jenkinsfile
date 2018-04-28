pipeline {
    node {
       stages {
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
