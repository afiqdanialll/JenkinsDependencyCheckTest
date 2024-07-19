pipeline {
  agent any
  stages {
    stage('OWASP DependencyCheck') {
    //   steps {
    //     dependencyCheck additionalArguments: '--format HTML --format XML --noupdate', odcInstallation: 'OWASP Dependency-Check Vulnerabilities'
    //   }
    steps{
        sh "ls -la"
    }
    }
  }  
//   post {
//     success {
//       dependencyCheckPublisher pattern: 'dependency-check-report.xml'
//     }
//   }
}
