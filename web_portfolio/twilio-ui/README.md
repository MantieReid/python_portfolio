# Twilio-Integration-UI

Here is a softphone with a flask backend that allows
one to send text messages, leave notes to themselves
and call others through twilio.

To use this UI you must sign up for twilio and get
a free number.  Once you do then you will be able to
include your account sid and auth token.

Configuration for the flask portion depends upon
a hidden.py file.  


first start the UI: \
    `$ npm start`

to start web server: \
    `$ cd ../twilio_integration` \
    `$ vi .hidden.py` \

```diff
- ⚠️ ⚠ As you may very well know, if the name of .hidden.py is changed\ don't forget to include it within the .gitignore file ⚠ ⚠
```

insert into the file: \
    `hidden_account_sid = {Your Account sid}` \
    `hidden_auth_token  = {Your Auth Token}` 

start the flask app by: \
    `$ python3 __main__.py`


## Default
![](https://github.com/phos-tou-kosmou/python_portfolio/blob/python/web_portfolio/twilio-ui/assets/vanilla.png)


## Phone Calls
![](https://github.com/phos-tou-kosmou/python_portfolio/blob/python/web_portfolio/twilio-ui/assets/number-slot-example.png)

## Send text messages over Twilio or to evernote, sticky notes, etc.

![](https://github.com/phos-tou-kosmou/python_portfolio/blob/python/web_portfolio/twilio-ui/assets/full-fledge.png)

### Future updates: 
    1. Working to integrate within CRM's.  First target will be Zoho CRM.
    
    2. Chrome extension 

    3. Allow integration choices for Publish Subscribe servies or WSS.