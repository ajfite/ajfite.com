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
            sh 'rsync -rltvh --delete _site/ /www/ajfite.com/www/'
         }
      }
   }
}
