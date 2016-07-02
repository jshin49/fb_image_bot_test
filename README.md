# fb_image_bot_test
Sending and receiving images example via Facebook Messenger Platform

First check out the [Quickstart Guide](https://developers.facebook.com/docs/messenger-platform/quickstart) provided by Facebook.

Second, mkdir config and add a default.json inside config with the following contents:

{<br/>
&nbsp;&nbsp;&nbsp;&nbsp;"appSecret": "YOURAPPSECRET",<br/>
&nbsp;&nbsp;&nbsp;&nbsp;"pageAccessToken": "YOURPAGEACCESSTOKEN",<br/>
&nbsp;&nbsp;&nbsp;&nbsp;"validationToken": "YOURVALIDATIONTOKEN"<br/>
}<br/>


## Running Locally
0. Install Node and NPM and ngrok (or localtunnel)
1. Run "sudo npm install" command to install external modules locally
2. Run "node app.js" to run the app
3. Enter localhost:8080 on the web url to check (All static files are served in the 'public' folder)
4. Enter ngrok http 8080 to tunnel a connection from https://foo.ngrok.io to localhost
5. Give https://foo.ngrok.io/webhook for your webhook verificaiton URL in the Messenger App settings
6. Now for every message, you can check the response and request through your console.

## Running on Heroku
0. Do steps 0~1 from above and install Heroku toolbelt from the Heroku website
1. Run "heroku login"
2. If existing repository, simply add a remote to heroku with this command: heroku git:remote -a YOUR_HEROKU_APP
3. Else, run the following codes

  - heroku git:clone -a image-bot-test && cd image-bot-test
  - git add . && git commit -am "make it better" && git push heroku master

4. Give https://yourheroku.herokuapp.com/webhook for your webhook verificaiton URL in the Messenger App settings
5. Voila :)

You can checkout our coding standards for [Node.js](nodejs.md) and [Python](python27.md).
