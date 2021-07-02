# DiscordAutoSender
Sends a message to any discord channel at set time intervals. This can be used to get endless SMH from the Spacemesh Tap.

Only works on Windows but can be easily modified to support other platforms.

# Quick start
You will first need to find your discord session key to authenticate your messages. Make sure to keep your session key private since if it's stolen it can be used to impersonate you on discord!

1. 打开chrome, 输入discord.com

2. 进入浏览器 "开发者工具"(F12) 之后在右边找到 Application 标签

3. 点击*toggle device toolbar icon*进入智能手机浏览视图或者使用快捷键 (Ctrl + Shift + M)

4. 刷新页面

5. 找到Storage -> Local Storage -> https://discord.com 向下滚动直到找到 *token* 然后复制，注意不需要引号 (大概张这个样子: `xyz.abcdefgh12345_abcdefgh12345abcdefg12345abcdefg12345`)

6. 编辑discord_auto_sender.bat 粘贴自己的 *token*到DISCORD_SESSION_KEY=

7. Set the CHANNEL_ID to the channel you want to send messages to. The channel id can be found by navigating to the channel in the browser and copying the id from the URL (for example the Spacemesh tap channel id is `623196575191007232`)

8. Set the MESSAGE you want to send, likely to be your Spacemesh wallet address

9. Set the TIMEOUT interval in seconds. Please don't use this script to spam servers, be sensible! (the spacemesh tap will only give you new coins every 3 hours so no point in setting this to less than 10800 seconds)

10. Double click *discord_auto_sender.bat* and you're away!

# Support the developer
I know this script is super trivial, but if you like it why not send me some SMESH!


## Spacemesh Address: 0xe8c429795a31ff22e2f9327d7b8a3b77ffed393f
