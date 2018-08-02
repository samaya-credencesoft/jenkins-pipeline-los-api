node {



    stage('Clone repository') {
        withCredentials([[$class: 'UsernamePasswordMultiBinding', credentialsId: 'samaya-credencesoft',
        usernameVariable: 'USERNAME', passwordVariable: 'PASSWORD']]) {

        sh 'echo uname=$USERNAME pwd=$PASSWORD'
        sh 'echo uname=$usernameVariable pwd=$usernameVariable'

        git clone 'https://samaya-credencesoft:Bishnu17@github.com/samaya-credencesoft/java-customer-onboarding.git'
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
