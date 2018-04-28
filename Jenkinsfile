node {
    stage('MyStage') {
        ansibleTower(
            towerServer: 'Tower-Prod',
            templateType: 'job',
            jobTemplate: 'Simple Test',
            importTowerLogs: true,
            inventory: 'myprod',
            jobTags: '',
            limit: '',
            removeColor: false,
            verbose: true,
            credential: '',
            extraVars: '''---
my_var:  "Jenkins Test"'''
        )
    }
}
