pipeline {
  agent any
  stages {
    stage('testing') {
      parallel {
        stage('testing') {
          agent any
          steps {
            echo 'testnig miylt'
            sh 'echo "secon"'
          }
        }

        stage('kkk') {
          steps {
            sh 'echo "ketilebis gineba"  '
            echo 'hmmmmm'
          }
        }

      }
    }

  }
}