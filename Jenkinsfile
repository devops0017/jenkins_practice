pipeline {
  agent any
  stages {
    stage('shell1 ') {
      steps {
        sh 'echo \'stage1 worked!!\''
      }
    }

    stage('Shell2') {
      steps {
        sh 'echo \'Stage2 Worked!!\''
      }
    }

    stage('bum bum') {
      steps {
        sh '''echo \'Stage2 Worked!!\'
'''
        sh 'echo \'Stage3 step 2 worked!!\''
      }
    }

  }
}