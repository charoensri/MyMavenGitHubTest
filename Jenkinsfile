pipeline {
  agent any
  stages {
    stage('') {
      steps {
        git(url: 'https://github.com/charoensri/MyMavenGitHubTest/', branch: 'Master', changelog: true, credentialsId: '6ff5810095d0d26b099a8e69edcdb4f81e72a1d7', poll: true)
      }
    }
  }
}