# Telegram Message Sender

**Telegram Message Sender is a simple web application that allows you to send messages to multiple Telegram channels using a Telegram bot.**

# How To Use

1. **Create a telegram bot using *BotFather*:**
   1.1. Assume the bot name is **my_bot**.
   1.2. Save the **bot_token** for later use.
   1.3. Add **my_bot** as admin to your channels.
   1.4. Send **/my_id @my_bot** to each channel.
   1.5. Navigate to https://api.telegram.org/bot**bot_token**/getUpdates using the browser to get channel IDs.
     **Example:** https://api.telegram.org/bot6111399770:AAHIe25255jhEj6GBvtGO9tjL_xkYE/getUpdates
 2. **Edit the code:**
		 2.1. Assign the **token** variable using **bot_token**.
		 2.2. Fill your channel IDs in the **channels**  array.
 3. **Now run the program using VSCode or any other way you prefer**. 
