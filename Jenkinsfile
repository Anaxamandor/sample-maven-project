// pipeline {
//     agent any 
//     stages {
//     stage('maven install') {
//       steps {

//         sh 'mvn clean install'

//       }
//     }

//   }
// }

pipeline {
  agent any
  stages {
  stage('maven install') {
    steps {
      withMaven(maven: 'maven3') {
    sh 'mvn clean install'
}
    }
  }

}

}


