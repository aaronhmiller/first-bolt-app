### ngrok advice
Startup ngrok on port 3000 b/c that's where the Slackbot is running
ngrok http --domain=unbiased-dane-closely.ngrok-free.app 3000

### setting up views
`https POST slack.com/api/views.publish -A bearer -a SLACK_BOT_TOKEN < home-view.json`
