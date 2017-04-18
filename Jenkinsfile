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
        sh '''${tool name: 'sbt-0.13.13', type: 'org.jvnet.hudson.plugins.SbtPluginBuilder$SbtInstallation'}/bin/sbt compile test
'''
      }
    }
    stage('Unit tests') {
      steps {
        sh 'gfdgdfgdfg'
      }
    }
    stage('Release') {
      steps {
        sh 'fgdgdsfg'
      }
    }
  }
  environment {
    Version = 'fr.33'
  }
}