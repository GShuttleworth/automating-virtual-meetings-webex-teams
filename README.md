# Automating the creation of virtual meetings with Webex Teams

As many physical meetings have been cancelled, we are all using collaboration tools to keep meetings, conferences and events going, most likely, doing this through Webex teams.
But digitising tens or hundreds of meetings can introduce a LOT of admin overhead if you do this one at a time. Cut the manual overhead and save yourself some time. Deliver your virtual meeting rooms using code. Python code.

This code creates Webex Teams rooms and invites the appropriate participants by importind meeting data from a spreadsheet, all through the Webex Teams APIs and a some simple python code.

You don't need to be a Python whizz to use this, it's ready to be copied and implemented with your own data. If you are confident with Python, this works as a great base structure for you to enhance to your specific needs.

## What is Webex Teams?

Cisco Webex Teams is a powerful all-in-one collaboration tool that allows messaging, instant/scheduled video conferencing, interactive and simultaneous whiteboarding and screen/file sharing, all with security built in.
What's even better is that it exposes APIs which make things so much simpler for us :) 
In this code we leverage a Bot to create the virtual rooms, add the participants and send a welcome message.

## How to create a Bot

On the [Webex developer page](www.developer.webex.com), sign in, select 'Start Building Apps' -> 'Create New App'. Fill in the simple form (be sure to save your Bot Token somewhere safe, as you will need to substitute that into the code) and voilà, your bot will be ready!

#### Do get in touch and let us know how it goes!
