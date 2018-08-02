node {
    def app

    stage('Clone repository') {
       sh 'echo "Clonig Repo ....."'
       git branch: 'master',
       credentialsId: 'samaya-credencesoft'
       url: 'git@github.com:samaya-credencesoft/java-customer-onboarding.git'
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
