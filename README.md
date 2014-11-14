![Alt](https://lh4.googleusercontent.com/-PVw-ZUM9vV8/UuWeH51os0I/AAAAAAAAD6M/0Ikg7viJftQ/w1286-h566-no/hackathon-starter-logo.jpg)
Hackathon Starter [![Dependency Status](https://david-dm.org/wesleyduff/hackathon-boilerplate.png)](https://david-dm.org/wesleyduff/hackathon-boilerplate) [![Build Status](http://img.shields.io/travis/wesleyduff/hackathon-boilerplate.svg?style=flat)](https://travis-ci.org/wesleyduff/hackathon-boilerplate) [![Analytics](https://ga-beacon.appspot.com/UA-47447818-2/hackathon-starter?pixel)](https://github.com/igrigorik/ga-beacon)
=======================

> This repo is based of off Sahat's Hackathon-starter.
> His repo can be found [here](https://github.com/sahat/hackathon-starter)

:octocat: &nbsp;**Live Demo**: http://hackathonstarter.herokuapp.com 

## Frameworks used
<a href="https://camo.githubusercontent.com/16800ac336b7e71aa4dec640abdd44505af0fe25/687474703a2f2f69616e646f75676c61732e636f6d2f70726573656e746174696f6e732f7079636f6e6361323031322f6c6f676f732f73656e64677269645f6c6f676f2e706e67" target="_blank"><img src="https://camo.githubusercontent.com/16800ac336b7e71aa4dec640abdd44505af0fe25/687474703a2f2f69616e646f75676c61732e636f6d2f70726573656e746174696f6e732f7079636f6e6361323031322f6c6f676f732f73656e64677269645f6c6f676f2e706e67" width="200" data-canonical-src="http://iandouglas.com/presentations/pyconca2012/logos/sendgrid_logo.png" style="max-width:100%;"></a>
- Go to (https://www.sendGrid.com)
- Sign up and *confirm* your acccount via the activation email
- Enter your SendGrid _Username_ and _Password_ into 
```javascript
config/secrets.js
```
- You can view the web api [here](https://sendgrid.com/docs/API_Reference/Web_API/index.html)

___

<a href="https://camo.githubusercontent.com/11659862cd7bdf1c50b7aeac5b13964252deebfc/687474703a2f2f696d616765732e676f6f676c652e636f6d2f696e746c2f656e5f414c4c2f696d616765732f737270722f6c6f676f36772e706e67" target="_blank"><img src="https://camo.githubusercontent.com/11659862cd7bdf1c50b7aeac5b13964252deebfc/687474703a2f2f696d616765732e676f6f676c652e636f6d2f696e746c2f656e5f414c4c2f696d616765732f737270722f6c6f676f36772e706e67" width="200" data-canonical-src="http://images.google.com/intl/en_ALL/images/srpr/logo6w.png" style="max-width:100%;"></a>
- Visit [Google Developers Console](https://console.developers.google.com)
- click **CREATE PROJECT** button
- Enter *Project Name*, then click **CREATE**
- Select *APIs & auth* from the sidebar and click on *Credentials* tab
- Click **CREATE NEW CLIENT ID** button
 - **Application Type:** Web Application
 - **Authorized Javascript origins**: http://localhost:3000
 - **Authorized redirect URI**: http://localhost:3000/auth/google/callback
- Copy and past *Client ID* and *Client* secrete keys into `config/secrets.js`
