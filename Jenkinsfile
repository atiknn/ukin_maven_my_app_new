node{   
    stage('slack notification'){        
        slackSend  botUser: true, channel: '#jenkins-pipeline-demo-2', color: 'good', failOnError: true, message: 'test message 2 to from jenkins', tokenCredentialId: 'slack-pwd'
    }
   
}
