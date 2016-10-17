## Tingbot Webhook 🎣  Server

The hook server for webhook support in [tingbot-python](https://github.com/tingbot/tingbot-python).  A small lightweight python app that utilizes `HTTPServer`, `zmq` for sockets, and `shelve` for persistant storage.

#### Public Webhooks:

Currently Tingbot provides free public access to this functionality on a subdomain of [Tingbot.com]() e.g.

**_http://webhook.tingbot.com/my-hook_**
 
`my-hook` can be any valid URL where information will be posted for the Tingbot [webhook](http://tingbot-python.readthedocs.io/en/latest/webhooks.html#webhook) to recieve.
