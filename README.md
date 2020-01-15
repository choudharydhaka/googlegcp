# Introduction
This program allows you to create/trigger a file on a remote system using WSO2 ESB product. Since WSO2 has production under apache license so we can use them anywhere without any trouble.

Think about the scenarios:
> Use your mobile device to give command to your systems using Google assistance. 
example:
```
Hey Google!
Please spin up one of the container with name wso2esb
```
Above command to Google home/assistance allows to intract with dialogflow and then dialogflow sends a REST API call to WSO2ESB. REST API will run a command on local/remote system and spins a container with `dhaks/wso2esb:1.0.0`

## Prerequisite
You must have a little bit knowledge of Google dialogflow and WSO2 ESB

# Run
Step 1 : Run WSO2 ESB API on a publically IP/Domain address
Step 1 : Import Hello_world.zip file to your dialogflow and update API address with your ESB public address
Step 2 : Run Dialogflow using web browser
