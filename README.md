If the asset in your "application.css" file is not present in the asset pipeline after running "yarn install" and "bundle install" followed by "bundle exec rails s," there are a few potential causes and troubleshooting steps you can take:

1. Restart the server: After running "yarn install" and "bundle install," make sure to restart your Rails server using the "bundle exec rails s" command. Sometimes, changes to the asset pipeline require a server restart to take effect.
2. Precompile assets: If you are running your application in production mode, try precompiling your assets manually by running the following command: bundle exec rake assets:precompile
3. You can also try following commands : yarn add asset
yarn add websocket
