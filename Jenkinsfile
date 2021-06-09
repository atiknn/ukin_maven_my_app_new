node{   
    stage('slack notification'){        
      
        def attachments = [
  [
    text: 'I find your lack of faith disturbing!',
    fallback: 'Hey, Vader seems to be mad at you.',
    color: '#ff0000'
  ]
]

slackSend(channel: "#jenkins-pipeline-demo-2", attachments: attachments)
    }
   
}
