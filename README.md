Node.js wrapper for the Google Contacts API.

# Install

    npm install google-contacts-api

# Usage

```javascript
var contacts = new GoogleContacts({ token : req.token });
contacts.getContacts(function(err, contacts) {
    // ...
});
```
