# Discordapp TokenGrabber
  - Simple but "advanced" 
     # 1.0 Deployed!
       + **New ability: Locks the user completely out of his account**
       + **New ability: Return data through a webhook**
       + **New ability: Remove 2FA (2FA accounts couldnt get their email & password changed, so i broke that layer)**
       + **New ability: Sends all the chrome data (login, email, password) through a webhook**
   
     # Whats next:
       + pywintypes.error: (87, 'CryptProtectData', 'The parameter is incorrect.') [Need to fix it]

# How to compile
 - In CMD: `pip install pyinstaller` & `pip install pyarmor`
 - Drag the main.py file to the desktop and in CMD: `cd desktop`
 - In CMD: `pyarmor pack -e " --onefile" main.py`, go to dist and grab your packed file!

# The program outputs as:

![Program Output](https://cdn.discordapp.com/attachments/490610729607495692/712621434824032337/unknown.png)
