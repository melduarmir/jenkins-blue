pipeline {
  agent {
    node {
      label 'gdgfdf'
    }
    
  }
  stages {
    stage('Preparation') {
      steps {
        git(url: 'sdfdsfds', branch: '*/stable')
      }
    }
    stage('Build') {
      steps {
        parallel(
          "Build": {
            sh '''${tool name: 'sbt-0.13.13', type: 'org.jvnet.hudson.plugins.SbtPluginBuilder$SbtInstallation'}/bin/sbt compile test
'''
            
          },
          "Unit tests": {
            sh 'fdsfsadfa'
            
          }
        )
      }
    }
    stage('Tickets') {
      steps {
        sh 'gfdgdfgdfg'
        node(label: 'gdgd') {
          echo 'gdfgd'
        }
        
      }
    }
    stage('Release') {
      steps {
        sh 'fgdgdsfgfgdsfg'
      }
    }
  }
  environment {
    Version = 'fr.33'
  }
}