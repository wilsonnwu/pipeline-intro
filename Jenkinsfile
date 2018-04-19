pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo "Hello ${MY_NAME}!"
      }
    }
  }
  environment {
    TEST_USER = credentials('test-user')
    MY_NAME = 'Mary'
  }
}