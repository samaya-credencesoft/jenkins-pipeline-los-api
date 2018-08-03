#!/usr/bin/env groovy
pipeline {
    agent {
        label 'linux'
    }
    options {
        // General build options
        buildDiscarder(logRotator(numToKeepStr: '25'))
        disableConcurrentBuilds()
        skipDefaultCheckout()
        timeout(time: 1, unit: 'HOURS')
        timestamps()
    }


    stage('Clone repository') {
        git url: "git@github.com:samaya-credencesoft/java-customer-onboarding.git",
        credentialsId: 'credencesoft-github-key-id'
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
