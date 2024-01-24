release: rake db:migrate
#web: bundle exec puma -C config/puma.rb
#worker: bundle exec sidekiq -c 5

web: /bin/bash -l -c "bundle exec puma -C config/puma.rb"
worker: /bin/bash -l -c "bundle exec sidekiq -e production -C config/sidekiq.yml"