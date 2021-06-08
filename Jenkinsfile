node{
    stage('SCM checkout'){
        git 'https://github.com/atiknn/ukin_maven_my_app_new'
    }
    stage('Compile Package'){
        //get maven home path
        def mavenHome = tool name: 'maven-3.8', type: 'maven'
        sh "${mavenHome}/bin/mvn package"
        
    }
    stage('slack notification'){
         slackSend channel: '#jenkins-pipeline-demo-1', color: 'good', message: 'test slack message', tokenCredentialId: 'slack-pwd'        
    }
   
}
