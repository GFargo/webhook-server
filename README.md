## Tingbot Webhook 🎣 Server

The hook server for webhook support in [tingbot-python](https://github.com/tingbot/tingbot-python).  A small lightweight python app that utilizes `HTTPServer`, `zmq` for sockets, and `shelve` for persistant storage.


### Using Webhooks:

Currently Tingbot provides free public access to this functionality on a subdomain of [Tingbot.com]() e.g.

**_http://webhook.tingbot.com/my-hook_**

`my-hook` can be any valid URL where information will be posted for the Tingbot [webhook](http://tingbot-python.readthedocs.io/en/latest/webhooks.html#webhook) to recieve.


- More on Tingbot webhooks can be found [here](http://tingbot-python.readthedocs.io/en/latest/webhooks.html).


## Private Webhooks:

Currently the webook server defaults to Public, allowing anyone to retrieve via a `GET` request or simply by visiting the [webooks page](http://webhook.tingbot.com/webhook) in their browser.

If you are privately hosting your own webhook 🎣 server and wish to hide the current data stored you must change the `_is_private` variable to `True` instead of `False`.


