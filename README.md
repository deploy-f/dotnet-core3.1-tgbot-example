# Example of the Telegram chatbot for .NET 3.1

 **How to launch a bot**
 1. Clone this repo
 2. Build project in Release mode
   ```dotnet publish -c Release -o publish```
 3. Go to publish directory and create an zip-archive of published source files
 4. Upload your zip-archive to deploy-f.com
 5. Configure bot token
    * with environment variable: `BotSettings__BotToken`=`bot_token` <br>
    or <br>
    * with edited appsettings.json file
 6. Press Start button
