pipeline {
    agent any

    // Should not be included to the actual
    environment {
      env.PATH = env.PATH + ";c:\\Windows\\System32"
    }

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
