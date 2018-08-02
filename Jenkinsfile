node {



    stage('Clone repository') {
        withCredentials([[$class: 'UsernamePasswordMultiBinding', credentialsId: '<CREDENTIAL_ID>',
        usernameVariable: 'USERNAME', passwordVariable: 'PASSWORD']]) {

        sh 'echo uname=$USERNAME pwd=$PASSWORD'
         }
       git url: 'https://github.com/samaya-credencesoft/Website.git'

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
