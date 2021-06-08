node{
    stage('SCM checkout'){
        git 'https://github.com/atiknn/ukin_maven_my_app_new'
    }
    stage('Compile Package'){
        sh 'mvn package'
    }
}
