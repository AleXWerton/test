node {
    stage('Build') {
      sh 'touch test1'  //
    }
    stage('Test') {
      sh 'touch test2'  //
    }
    stage('Deploy') {
      sh 'touch test3'  //
    }
    stage('Check') {
      sh 'ls -a'
      sh 'cd envs'
      sh 'ls -a'
    }
}
