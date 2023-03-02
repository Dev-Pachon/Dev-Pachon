pipeline {
  agent any
  stages {
    stage('Pre-Build') {
      steps {
        sh 'npm install'
        echo 'Installing Dependencies'
      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'npm run dev'
            echo 'Ajuuueee'
          }
        }

        stage('') {
          steps {
            echo 'Ajueee'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }

  }
}