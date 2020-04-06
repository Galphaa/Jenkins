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
          agent any
          steps {
            sh 'echo "ketilebis gineba"  '
            echo 'hmmmmm'
          }
        }

      }
    }

    stage('ketilebi') {
      parallel {
        stage('ketilebi') {
          steps {
            echo 'ramdariram'
            sleep 3
            sh 'echo "not error "'
          }
        }

        stage('mario') {
          steps {
            sleep 1
          }
        }

      }
    }

  }
}