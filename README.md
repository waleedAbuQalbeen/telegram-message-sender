# Telegram Message Sender

**Telegram Message Sender is a simple web application that allows you to send messages to multiple Telegram channels using a Telegram bot.**

# How To Use

1. **Create a telegram bot using *BotFather*:**
2.   Assume the bot name is **my_bot**.
3.   Save the **bot_token** for later use.
4.   Add **my_bot** as admin to your channels.
5.   Send **/my_id @my_bot** to each channel.
6.   Navigate to https://api.telegram.org/bot**bot_token**/getUpdates using the browser to get channel IDs.
     **Example:** https://api.telegram.org/bot6111399770:AAHIe25255jhEj6GBvtGO9tjL_xkYE/getUpdates
 7. **Edit the code:**
 8.  Assign the **token** variable using **bot_token**.
 9. Fill your channel IDs in the **channels**  array.
 10. **Now run the program using VSCode or any other way you prefer**. 
