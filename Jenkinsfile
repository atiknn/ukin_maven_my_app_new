node{   
    stage('slack notification'){        
       // slackSend  channel: '#jenkins-pipeline-demo-2', color: 'good', failOnError: true, message: 'test message 2 to from jenkins', tokenCredentialId: 'slack-pwd'
        slackSend botUser: true, 
  channel: 'jenkins-pipeline-demo-2', 
  color: '#00ff00', 
  message: 'Testing Jekins with Slack by att', 
  tokenCredentialId: 'slack-bot-token'
    }
   
}
