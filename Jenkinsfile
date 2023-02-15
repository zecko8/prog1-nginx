pipeline {
  agent {
    docker { image 'nginx' }
  }
  stages {
    stage('Test') {
     steps {
      sh 'wget https://raw.githubusercontent.com/zecko8/prog1-nginx/main/index.html'
      sh 'cp index.html /usr/share/nginx/html/index.html'
     }
    }
  }
}
