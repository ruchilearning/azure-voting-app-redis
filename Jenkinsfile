node {
  stage('Echo on master') {
    if (env.BRANCH_NAME == 'master') {
      sh(script: 'This is the master branch')
    } else {
      sh(script: 'This is NOT the master branch')
    }
  }
}
