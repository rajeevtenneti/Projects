pipeline {
  agent any
  stages {
    stage('Code checkout') {
      steps {
        sh '''git clone https://tejatenneti@bitbucket.org/tejadev101/jenkins101.git -b develop
git checkout feature/2to3 '''
      }
    }

  }
  environment {
    DEMO = '1'
  }
}