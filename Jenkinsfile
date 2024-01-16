pipeline {
  agent any
  stages {
    stage('GIT') {
      steps {
        git(url: 'git@github.com:Bichou90/Devops.git', branch: 'master', credentialsId: 'OPB')
      }
    }

  }
}