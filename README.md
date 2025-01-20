# Zenitel-Connect-Pro-XProtect-Event-Handler
This solution implements sending events triggered in Milestone XProtect VMS to a Node-red flow running on Zenitel Connect Pro server. Milestone XProtect is configured to trigger sending event to a webhook after the motion is detected on the camera, Node-red running on ZCP server receives event via webhook using HTTP IN node. After the event is received, warning message which is stored on ZCP server is played.
To test this flow, follow next steps : 
1. Ensure that XProtect is up and running
2. Ensure that events, rules and webhooks are properly configured in XProtect managment client.
3. Ensure the flow is deployed on Zenitel Connect Pro server, port 1880.
4. Ensure that nodes contain valid credentials and configuration.
5. Ensure that nodes contain valid directory numbers to play audio message.
