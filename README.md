# SSH-login-Signal-notification
Receive notification on Signal IM when login by SSH


1. Install Signal-cli (see https://github.com/AsamK/signal-cli)
2. Check if you have java installed (see https://github.com/AsamK/signal-cli/issues/107)
3. Register your phone with Signal using this command; signal-cli -u +[yournumber] register
4. When you receive the confirm code on your phone, confirm it by using this command;   signal-cli -u +[yournumber] verify [CODE]
Try to sent a message by typing; signal-cli -u +[yournumber] send -m "This is a message" +[friendsnumber]
When that work, we can continue.....
