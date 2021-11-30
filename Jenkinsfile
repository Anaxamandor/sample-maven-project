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
      withMaven {
    sh 'mvn clean install'
}
    }
  }

}

}
