node {

    stage('Clone repository') {
        git url: 'ssh://samaya-credencesoft@github.com/java-customer-onboarding.git',
        credentialsId: 'credencesoft-github-key-id'
         }
    }

    stage('Build image') {

      sh 'echo "Building Image ....."'
    }

    stage('Test image') {
        sh 'echo "Test Image ....."'
    }

    stage('Push image') {
        sh 'echo "Push image ....."'
        }

}
