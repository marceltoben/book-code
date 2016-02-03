# Automated Trading Bot Framework

The software is covered by the *Apache License* and is discussed in my book [Developing a Trading Bot using JAVA](http://www.leanpub.com/tradingbot)

##How to run the software

1. Download the source code.
2. Change the **tradingbot.properties** by configuring the email and twitter properties
3. Change the **tradingbot-oanda.properties** by configuring the oanda specific properties
4. Build the by executing script **buildbot.bsh**. The script uses maven. Please make sure its properly configured.
5. Run the bot using script **runbot-oanda.bsh**
