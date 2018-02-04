pipeline {
   agent any

   stages {
      stage('Build and Deploy') {
         steps {
            echo 'Updating Gemfiles...'
            sh 'BUNDLE_GEMFILE=Gemfile bundle install'
            echo 'Building and deploying'
            sh 'bundle exec jekyll build -d /www/ajfite.com/www/'
         }
      }
   }
}
