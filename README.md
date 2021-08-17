# nodejs-apps
Apps coded with Node.js developer language
__________________________________________________________________________

#sender-email.js

You are needed a node.js program to run this code.

## Methods
Initialize quick-email
```javascript
require('quick-email').init(user, password, host, port, ssl);
```

Send an email
```javascript
require('quick-email').sendEmail(path, subject, sender, to, variables, callback);
```
## How to run?
Use command ``` nodejs sender-email.js require('quick-email').init(user, password, host, port, ssl);``` to initalize, 
and ``` nodejs sender-email.js require('quick-email').sendEmail(path, subject, sender, to, variables, callback);``` to send a email.
