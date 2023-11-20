# Whatsapp Bot API

## Connection

To connect your account, run the code.
```bash
node index.js
```

It will generate a QR Code in the console. Scan the QR code by opening "Link a Device" option in WhatsApp.

## Working

Whenever a request is send to the API though the webpage(on user registration), the bot will automatically send the pre-defined message to the user.

## Configuration

### Message Config :
To configure the message which the bot sends, in the index.js file edit the "messageText" variable.
```javascript
const messageText = `*Welcome to Our Service!* \n\n` +
                    `*Thank you for signing up. Here are some important details:*\n\n` +
                    `*What's Next:*\n\n` +
                    `1. Explore our features and services.\n` +
                    `2. Contact our support team if you have any questions.\n` +
                    `3. Enjoy your experience with us!\n\n` +
                    `*Feel free to reach out if you need assistance or have any feedback.*\n\n` +
                    `🎉 *Happy exploring!* 🎉`;

//Replace the Message with your custom message, don't forget to add ` at opening and closing of the message.
// Use \n for line break.

```
### Image Config : 
To edit the image which the bot sends, in the index.js file edit the media.
```javascript
 const media = await MessageMedia.fromUrl("Replace here with your custom URL");
```

## More Information's

* The user account will not get banned by using this API method.
* Message can be send to users from different country/regions.
* There is no message limit per day. Its unlimited.
* The linked WhatsApp account can also be used as a normal.

