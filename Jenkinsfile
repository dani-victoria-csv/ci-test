pipeline {
    agent any

    stages {
      
      stage('Install') {
        steps {
          bat 'npm install'
        }
      }
      
      stage('Unit tests') {
        steps {
          bat 'npm run test'
        }
      }
      
      stage('Build') {
        steps {
          bat 'npm run build'
        }

      }

    }
}
