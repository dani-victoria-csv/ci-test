pipeline {

    agent any

    stages {
      
      stage('Install') {
        steps {
          sh 'npm install'
        }
      }
      
      stage('Unit tests') {
        steps {
          sh 'npm run headless-test'
        }
      }
      
      stage('Build') {
        steps {
          sh 'npm run build'
        }

      }

    }
}
