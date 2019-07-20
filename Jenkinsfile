pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''echo "My shell is: $SHELL"
echo "My current directory is pwd --- $PWD "
echo " My user is $WHOAMI --- $USER"'''
      }
    }
  }
}