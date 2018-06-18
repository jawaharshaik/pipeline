pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        sh '''cd vf-goop-portal-modules/themes/goop-theme
mv node_modules node_modules_fix
cp -r node_modules_fix ../blank-theme/'''
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}