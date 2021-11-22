pipeline {
  agent any
  stages {
    stage('BUILD') {
      steps {
        echo 'BUILDING'
      }
    }

    stage('DEPLOY') {
      steps {
        echo 'DEPLOYING'
      }
    }

    stage('RUN') {
      steps {
        sh 'sh \'echo "hello "\''
      }
    }

  }
}