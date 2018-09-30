pipeline {
  agent any

  stages {
    stage('Deploy') {
      when {
        branch 'master'
      }
      steps {
        sh "${env.JENKINS_SCRIPTS}/deploy-artifact.sh"
      }
    }
  }
}
