pipeline {
  agent {
    node { label 'workstation'}
  }

  stages {
    stage ('Build code') {
      steps {
        sh 'npm install'
      }
    }

    stage ('Unit Testing') {
          steps {
            echo "Unit Testing"
          }
    }


    stage ('Code Analysis') {
          steps {
            echo "Code Analysis"
          }
    }

    stage ('Security checks') {
          steps {
            echo "Security checks"
          }
    }

    stage ('Code Publish') {
          steps {
            echo "Code Publish"
          }
    }
  }

//   post {
//     always {
//
//     }
//   }



}