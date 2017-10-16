pipeline {
  agent {
    node {
      label '10.230.29.210'
    }
    
  }
  stages {
    stage('kenanFX2.2') {
      steps {
        sh '''#1/usr/bin/ksh

uname -a
ifconfig -a'''
      }
    }
  }
}