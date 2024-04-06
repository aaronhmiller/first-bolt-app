### npm & node refresher
the modules/packages/dependencies aren't loaded locally from the package.json 
until you run `npm install`
then you can run `node app.js`

### ngrok advice
Startup ngrok on port 3000 b/c that's where the Slackbot is running
ngrok http --domain=unbiased-dane-closely.ngrok-free.app 3000

### setting up views
`https POST slack.com/api/views.publish -A bearer -a SLACK_BOT_TOKEN < home-view.json`
