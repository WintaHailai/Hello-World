pipeline {
  agent any
  stages {
    stage('checkout ') {
      steps {
        git(url: 'https://github.com/WintaHailai/jenkins-fcc-readme.git', branch: 'main', poll: true)
      }
    }

  }
}