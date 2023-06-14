pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/tamartayar/project.git', branch: 'master')
      }
    }

    stage('build') {
      steps {
        sleep 5
      }
    }

  }
}