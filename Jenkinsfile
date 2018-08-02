node {
    def app

    stage('Clone repository') {
       sh 'echo "Clonig Repo ....."'
       sh 'git branch: 'master',
            credentialsId: 'samaya-credencesoft'
            url: 'ssh://git@github.com:samaya-credencesoft/java-customer-onboarding.git'
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
