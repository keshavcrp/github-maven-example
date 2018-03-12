pipeline {
  agent {
    node {
      label 'build '
    }
    
  }
  stages {
    stage('Test') {
      steps {
        sh '''echo "hi kesh I waqna deploy my file "

scp https://github/keshavcr/smaple/1.0-sanpshot.jar keshavm@10.1012.201/home/tyarget '''
      }
    }
  }
  environment {
    test = 'env'
  }
}