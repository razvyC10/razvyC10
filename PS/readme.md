# Configuration
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| platform        | An array containing all the platforms you want your grabber to work on.                                                                                | ["windows"] | array   |
| logout          | False - Do not log out delayed: Disconnect the next time you launch Discord Instant: Kill Discord and ask to reconnect                                 | "instant"   | boolean |
| inject-notify   | False - Does not send a message when the grabber has successfully injected True - Send a message when the grabber has successfully injected            | "true"      | boolean |
| logout-notify   | False - Does not send a message when the victim has successfully logged out True - Send a message when the victim has successfully logged out          | "false"     | boolean |
| init-notify     | False - Does not send a message when the grabber has been initialized in the victim discord client True - Send the message                             | "false"     | boolean |
| embed-color     | The embed color in decimal!                                                                                                                            | "8359053"   | string  |
| disable-qr-code | False - The victim will have access to the authentication QRCode (not recommended) True - The victim will not have access to the authentication QRCode | "true"      | boolean |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|