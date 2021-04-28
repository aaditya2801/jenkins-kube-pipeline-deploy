
pipeline {
agent any
  stages {
    stage('abc'){
      steps {
      sh "kubectl apply -f deploy.yaml --kubeconfig admin.conf"
      }
    }
  }

}
