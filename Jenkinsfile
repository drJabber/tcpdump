pipeline {
  agent any
  stages {
    stage("build") {
        agent {
            docker {
                image "aflplusplus/aflplusplus"
            }
        }
        steps {
          echo "hello from docker!"
        }
    }    
  }
}
