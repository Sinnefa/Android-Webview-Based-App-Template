# Android Webview Based App Template

Make your Android App using HTML and Javascript (Jquery and more)

This project contains an app template to be used in Android Studio. It is an empty app which exploits the Android WebView to offer an easy way to implement Android apps. You can simply create your app using HTML and Javascript, any library or framework you want. If you are done with your web app, you can just move it in the "assets" directory, compile with Android Studio and you are ready to deploy your app.

Differently from other similar templates you can find out there, I wanted to develop this so that it works like an ordinary app. It combines the easiness of web development with Android. This template uses cookies to save variables. This allows you to simply migrate web apps to Android as cookies are generally an easy way to keep session variables.

# Advantages

1. You can use HTML, Javascript to develop the App as a native Android App.
2. You can use cookies to save variables.
3. Back button to navigate backward.
4. Mail-to: hyperlink opens the generic intent "Send" ans plain text.

# Things to remember

1. Your web app should be mobile friendly. I suggest the following header
```
<meta http-equiv="X-UA-Compatible" content="IE=edge" />
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<meta name="viewport" content="width=device-width">
```
2. I recommend configuring the <body> tag as follows
```
<body leftmargin=0 topmargin=0 rightmargin=0 bottommargin=0 style="margin:0;" onload="">
```
3. Rename your App package as you prefer
4. Edit Manifest and configuration files accordingly
  
# Example App
Pinguino app was made with this template
https://play.google.com/store/apps/dev?id=8757649835536160943
