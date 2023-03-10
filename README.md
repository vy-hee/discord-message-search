# discord-message-search

This is a Python script that allows you to search for specific keywords in your Discord messages and get the folder name and the ID of the user in which the keyword was found.

## Requirements
- Copy of your Discord Data ([How to download your discord data](https://support.discord.com/hc/en-us/articles/360004027692-Requesting-a-Copy-of-your-Data))

## Usage
1. Download or clone the repository
2. Open the command prompt or terminal in the folder where the script is downloaded
3. Run the command `py main.py` or `py main.py "folderPath"` ('folderPath' is location of where you extracted your discord data, paste the path of "messages" directory. eg: `py main.py "D:\discordData\messages"`)
4. Enter your Discord ID when prompted
5. Enter the channel type '0' for Server and '1' for DM
6. Enter the keywords you want to search for (multiple keywords should be separated by commas)

The script will then search for the keywords in all the messages that you have sent and return the folder name and the ID of the user to whom you sent the message/keyword.


## Note
For the script to work, you need to have the discord data downloaded.

## Conclusion
This script can be useful for anyone who wants to search for specific keywords in their Discord messages, and get the folder name and the ID of the user in which the keyword was found. With this script, you can easily search through your messages and find the information you need without having to manually search through all the messages.

Discord Id can be used to find Discord tag and few other info about the user.
- Copy the Id provided by the script
- Paste it on [Discord Lookup](https://discord.id/) to find the discord tag or any other info