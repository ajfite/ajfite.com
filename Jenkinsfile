pipeline {
   agent any
   properties([pipelineTriggers([githubPush()])])

   node {
       git url: 'https://github.com/Goldman60/ajfite.com.git', branch: 'master'
   }
   stages {
      stage('Build') {
         steps {
            echo 'Building...'
            sh 'jekyll build'
         }
      }
      stage('Deploy') {
         steps {
            echo 'Deploying...'
            sh 'cp -r _site/* /www/ajfite.com/www/'
         }
      }
   }
}
