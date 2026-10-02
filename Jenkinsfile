pipeline {
  agent any
  stages {
    stage('Checkout info') { steps { sh 'git log --oneline -3' } }
    stage('Build') { steps { echo "Branch: ${env.BRANCH_NAME}" } }
  }
}