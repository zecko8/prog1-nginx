pipeline {
  agent {
    docker {image 'nginx'}
  stages {
    stage('Test') {
      steps {
        sh 'echo ciao > /usr/share/nginx/index.html'
     }
    }
  }
}
