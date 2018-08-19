# Home-Automation
IOT Based Home Automation With Google Assistant/ Cortana/ Alexa

https://learn.adafruit.com/adafruit-io-basics-feeds/creating-a-feed
-


After Creation of Feed Follow this Steps:
-
#IFTTT SETUP
-
Login With ifttt.com (If This Then That)
Signup/ Signin to adafruit.io
Once you have signed in, visit ifttt.com/adafruit and click the Connect button to connect your IFTTT account to Adafruit IO.
You will be redirected to your Adafruit account page, and will be asked to authorize IFTTT. Click the AUTHORIZE button to grant access.
You will then be redirected back to IFTTT, and should see a Channel connected! message at the top of the page.
Next, navigate to your personal IFTTT Applet page https://ifttt.com/my_applets to start the Applet creation process.
Click the Create a Applet button
Click the blue THIS block of text to get started. (Step-1)
Search and Select the Google Assistant/ Cortana/ Alexa channel.
Login With Your Respective Account and Authorize.
Click on Say a simple phrase. (Step-2)
Enter the Phrase and the Response.
Then, click the blue THAT block of text to select what happens when the Above Trigger occurs.
Search and Select the Adafruit IO channel. (Step-3)
Click Send data to Adafruit IO. (Step-4)
Select the Feed Name and Value to be sent ie. 0 for off 1 for on (Step-5)
Review and Finish the Applet. (Step-6)

#The Above Step-1 to Step-6 are to be Repeated Twice for Every Different Device To be Controlled.
-
#After This Setup Edit the Sketch According to Your Need.
Fill in the necessary places as Commented. 
Upload The Sketch On ESP8266 or any WiFi Development Device.
