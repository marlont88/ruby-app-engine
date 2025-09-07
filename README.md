# ruby-app-engine
Sinatra app deployed to GCP App Engine via Cloud Shell
git clone https://github.com/yourusername/ruby-app-engine-demo.git
cd ruby-app-engine-demo
bundle install
runtime: ruby
env: flex
entrypoint: bundle exec ruby app.rb
gcloud config set project [hello world]
gcloud app create --region=us-central
gcloud app deploy
gcloud app browse
