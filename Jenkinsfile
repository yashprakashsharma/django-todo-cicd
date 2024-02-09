pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''sudo docker build . -t todo-app
sudo docker run -p 8000:8000 -d todo-app'''
      }
    }

  }
}