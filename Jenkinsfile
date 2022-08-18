pipeline {
  agent any
  stages {
    stage('Checkout Scm') {
      steps {
        git 'https://github.com/iftikhar-cheetay/testing.git'
      }
    }
    stage('Shell script 0') {
      steps {
        sh '''ls
cat index.html
'''
      }
    }
  }
  post {
    always {
      echo 'No converter for Publisher: jenkins.plugins.publish_over_ssh.BapSshPublisherPlugin'
    }
  }
}
