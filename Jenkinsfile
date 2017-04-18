pipeline {
  agent {
    node {
      label 'ala'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        git(url: 'gitulr', branch: '*/master')
        sh 'fdsfdsfdsfds'
        node(label: 'zzzz') {
          sh 'gfdgfdg2222'
        }
        
      }
    }
  }
}