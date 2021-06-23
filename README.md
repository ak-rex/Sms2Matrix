<a href="https://matrix.to/#/#smsmatrix:matrix.org">
    <img src="https://img.shields.io/badge/Chat-On%20Matrix-green"
        alt="Chat on Matrix"/>
</a>

# Sms2Matrix
A simple SMS & MMS &lt;--> Matrix bridge.

This app bridges all sms messages to matrix. For every (new) text conversation contact the bot will open a private 1:1 room and sends the incoming messages to that room. Any messages sent in that room by the matrix user will then be sent to the contact via SMS.  
As currently there is no end-to-end encryption implemented in this app, for privacy reasons it is preferable to use it with your own Matrix server. Your data-in-transit however will always be safe as they are encrypted using https over matrix -- provided the Matrix server is configured properly.

<a href="https://play.google.com/app/com.martindaleresearch.sms2matrix">
    <img src="https://www.gstatic.com/android/market_images/web/play_prism_hlock_2x.png"
        alt="Get it on the Play Store" height="80"/>
</a>

# Set up
- Create an account on a homeserver
- Install this app (compile the apk from source or from the [Play Store](https://play.google.com/app/com.martindaleresearch.sms2matrix))
- Grant the app all the necessary permissions
- Type in the needed info in the app
  - Bot Username: is the username of the just created user
  - Bot Password: is the password of the just created user
  - Homeserver url: is the url of the homeserver where the user is created
  - Your username: is where you want to forward all yous text message to
  - Devicename: is the devicename wich the api will use
- Press save
- Now all your text messages will be bridged
- [optional] Disable battery optimisations for the app. so the app wont be killed by Android.
