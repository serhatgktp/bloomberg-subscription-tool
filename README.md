# bloomberg-subscription-tool

This is a tool designed by one of my friends (for his use as a technical analyst intern at CIBC) that I have contributed to

Checks the subscription function of Bloomberg and automatically generates reports when a feed issue occurs

The check analyzes 3 values

First analysis is done with BID and ASK values. BID must always be less than ASK. If ASK-BID <= 0 then there is a feed issue at Bloomberg and that issue needs to be taken care of

The second analysis is the VWAP value check. The time stamp of VWAP is checked if the value is Null. If there is not a valid time stamp, that is another feed issue to be fixed

# Contribution

I worked on:
- retrieving information from the 'msg' data structure and setting respective values in the equity dictionary
- checking for error conditions and recording incident information

# -Demo

A demo of this application is not available due to the confidentiality of the data that is retrieved
