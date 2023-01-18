# RedpanSoftware.com's - Red Snap! Twitch Clip Command Software

If you've always wanted a clip command that let you use hotkeys regardless of what window is open. This is the software for you. 

# Features

- !clip - chat command
- lctrl+c default hotkey for making clips (there's a sound on a successful clip)


# Installation

1. Go to https://dev.twitch.tv and authenticate with the account you stream with
2. Click on **Applications**
3. Click **Register Your Application**
4. In the **Name** field, name it w/e you want, **RedSnap - Username** works
5. **OAuth** needs to be http://localhost:**PORT** from the config.yml file, default is **4040**
6. Hit **Add** 
7. Under **Category** select **Chatbot**
8. You aren't a robot lol..
9. Hit **Create**
10. Go to the manage mage for your application once you're there and hit "New Secret" copy your **Client Secret** and your **Client ID* then insert them in their respective place inside the config
11. Inside the config.yml change the **channel** and the **username** field to lowercase version of your channel.
12. Set post to chat to **true** or **false** if you want it to post anything to chat. Recommended to keep this on.
13. **chatCommand** can be changed to something else if you want. 

# Authenticating

1. Once the config is setup w/ the correct port, client id, client secret and channel/username information you can start the application.

2. Hit the **Authenticate** button once the app first starts up

3. It'll open a browser tab asking you to authorize the application. After you do this wait a bit after you go through twitch's OAuth prompts. Then the tab should close and the application should update to a greyed out authentication button. Which means you logged in successfuly!

4. You can logout and reauthenticate if something's weird on the 2nd page.

# Setting hotkey

1. Ghetto, but go to the hotkey tab and press up to 4 unique keyboard buttons. (mouse buttons not supported yet, working on something - need testers to get information on how mice work lol)
2. Once you've found the hotkeys you want hit save and you're done.

3. **Note**: clips won't happen if you're still setting your hotkey, switch back to the authenticaiton tab for the applicaiton to work.

4. Lastly you can minimize the app to your system tray and call it a day. :) 

Enjoy ! Report bugs by creating a new issue in the issue tracker and I'll figure out how to handle that.