pipeline {
  agent ec2-agent
  stages {
    stage('Build') {
      steps {
        echo "building"
        sleep 2
      }
    }
    stage('Test') {
      steps {
        echo "testing"
        sleep 2
      }
    }
    stage('Deploy') {
      steps {
        echo "deploying"
      }
    }
  }
}
