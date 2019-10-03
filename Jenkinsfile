node {
    checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '1dd9855d-79bd-45a0-8141-f3d8933d6c67', url: 'https://github.com/AleXWerton/test']]])
    stage('Build') {
      sh 'touch test1'
      sh 'touch test11'  //
    }
    stage('Test') {
      sh 'touch test2'  //
    }
    stage('Deploy') {
      sh 'touch test3'  //
    }
    stage('Deploy') {
      sh 'ls -a'
      sh 'cat test.yml' //
    }
}
