# Lifeguard Messenger

Lifeguards must always be ready to handle an upcoming emergency or first aid situation. My local beach stays prepared by reviewing possible scenarios and their treatments, but the studying process involves flipping through a thick Red Cross First Aid manual to find the correct responses. Because this process is slow and tedious, and because quick and accurate treatment is essential in an emergency situation, I created this Lifeguard SMS Messenger. This messenger can receive a text from a lifeguard detailing a scenario, such as "heart attack" or "dog bite," and will respond with the proper treatment. Whether it is used for studying or in emergency situations, I hope this bot will contribute to lifeguard efficiency and accuracy in the future.

See the messenger in action [here](https://drive.google.com/file/d/1sIkFuaLDHSfj0gsXDTpLPJaf1r3CLSGd/view?usp=sharing)! (Will open link to Google Drive)

# Prerequisites

To recreate this messenger, the following is required:

1. A device that can receive SMS messages
2. Twilio account and Twilio phone number
3. An sms-webhook service. I used ngrok to test this project, and will be using it as an example below.

If you are a local Parks & Recreation employee who wishes to use the messenger I have developed, please send an email to hannah.jiang1298@gmail.com.

# Running the Project

To start the ngrok proxy, type the following into the Terminal. Note that the port number (in this case, 5050) can be any port that is not currently in use on your computer. I found that ports 3000 and 5000 both worked fine.

```
ngrok http 5050
```

This will cause the following screen to pop up:

![alt text](https://github.com/hannahrjiang/markdown-here/raw/master/src/common/images/TerminalView.png "Termial View")
