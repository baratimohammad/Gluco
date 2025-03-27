First run the Catalogue,
Then GlucoSubscriberInflux,
Then TBotAdaptor,
Then main (which batch runs three instances of clients enabled by the file GlucoSensNPubNRest)

The telegram bot is accessible from @HealthInsulinBot. The authentication credintials are specified in main.py. They also can be accessed from catalogue in "patients".
