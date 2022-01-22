pipeline {
  agent any
  stages {
    stage('error') {
      agent {
        node {
          label 'nwc-test-server'
        }

      }
      steps {
        sh 'cp -r lua /data/compose/4/TTTDev/garrysmod/addons/ulx/'
        sh 'chown -R 10000:10000 /data/compose/4/TTTDev'
      }
    }

  }
}