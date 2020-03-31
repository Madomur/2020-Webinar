pipeline  {
  agent any

  stages {
    stage('build') {
      steps {
        echo "build App"
      }
    }

    stage('test_static'){
      steps {
        echo "static test app"
      }
    }

    stage('test_dynamic'){
      steps {
        echo "dynamic test app"
      }
    }

    stage('deploy'){
      steps {
        echo "deploy App"
      }
    }
  }
}
