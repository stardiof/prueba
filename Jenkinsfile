pipeline {
  agent any
  stages {
    stage('Build'){
      steps{
        sh "docker build -t stardiof/pokedex-flask:${env.BUILD_NUMBER} ."
      }
    }
  }
}
