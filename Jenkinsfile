node {
    def app

    stage('Clone repository') {
       git branch: "master",
       credentialsId: "samaya-credencesoft"
       url: "https://github.com/samaya-credencesoft/java-customer-onboarding.git"
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
