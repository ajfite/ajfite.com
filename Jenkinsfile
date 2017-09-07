pipeline {
   agent any

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
            sh 'cp -r _site/* /www/ajfite/www'
         }
      }
   }
}
