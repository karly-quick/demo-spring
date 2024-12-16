pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo "building"
      }
    }
    stage('Test') {
      steps {
        echo "testing"
      }
    }
  }
}




//   pipeline {
//     agent { docker { image 'maven:3.9.9-eclipse-temurin-21-alpine' } }
//     stages {
//         stage('build') {
//             steps {
//                 sh 'mvn --version'
//             }
//         }
//     }
// }
  // stages {
  //   stage('Build') {
  //     steps {
  //       script {
  //         docker.build("dylansnyk/demo-spring:latest")
  //       }
  //     }
  //   }
    // stage('Install and Run Snyk') {
    //   steps {
    //     withCredentials([string(credentialsId: 'snyk-insights-api-token', variable: 'SNYK_TOKEN')]) {
    //       sh '''
    //         # Install Snyk
    //         curl -Lo snyk https://static.snyk.io/cli/latest/snyk-linux
    //         chmod +x snyk

    //         env
            
    //         docker image ls
  
    //         # Run Snyk
    //         ./snyk auth ${SNYK_TOKEN}
    //         ./snyk container monitor dylansnyk/demo-spring:latest --tags="component=pkg:dylansnyk/demo-spring@main" --file=Dockerfile -d
    //       '''
    //     }
    //   }
    // }
//   }
// }
