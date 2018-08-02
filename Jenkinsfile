node {



    stage('Clone repository') {
        withCredentials([[$class: 'UsernamePasswordMultiBinding', credentialsId: 'samaya-credencesoft',
        usernameVariable: 'USERNAME', passwordVariable: 'PASSWORD']]) {

        sh 'echo uname=$USERNAME pwd=$PASSWORD'
        sh 'echo uname=$usernameVariable pwd=$usernameVariable'

        https://$USERNAME:$PASSWORD@github.com/$USERNAME/java-customer-onboarding.git
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
