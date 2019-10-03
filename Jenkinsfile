pipeline {
    agent any //docker blablabla, kdyz pres docker
    /*{docker {
      image 'node:8-alpine'
      args '-p 3000:3000'}
    }
    */

    environment {
    CI = 'true'
    }

    stages {
        stage ('install') {
          steps {
            bat 'npm install'
          }

        }
    }
}
