pipeline {
  agent any
  stages {
    stage('pull service code') {
      steps {
        dockerNode(image: 'pytorchImage') {
          build 'Batch Job'
        }

      }
    }
  }
}