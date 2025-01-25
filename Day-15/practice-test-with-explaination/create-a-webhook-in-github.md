WEBHOOKS:
Webhooks allow external services to be notified when certain events happen. When the specified events happen, we'll send a POST request to each of the URLs you provide.

GitHib -- Repo -- Setings -- Webhook -- Add Webhook  --  fill the details

payload url - http://3.93.173.58:5000/createJira (ec2 instance public ip)
content type - app/json
which event would you like to trigger this webhook? - issue comment (for testing added commit comments)
