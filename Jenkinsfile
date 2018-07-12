pipeline {
  agent {
    node {
      label 'new-slave'
    }

  }
  stages {
    stage('chkout') {
      steps {
        sh 'git clone https://github.com/gkdba87/springboot-maven3-centos.git'
        sh 'pwd'
      }
    }
  }
}