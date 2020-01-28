## Head to the interface

Here is an example ```.js``` implementation [online](https://www.eclipse.org/paho/clients/js/utility/).

Tip! Split 2 windows: we'll use one for subscription and the other for publishing.
```
Host:
mqtt.poc.kpn-dsh.com

Port:
8443

Client ID:
Leave it to default!

Path:
/mqtt

Username:
Make up one!

Password:
You'll receive them!

Keepalive:
60

Timeout:
3

TLS:
tick

Clean session:
tick

Automatic Reconnect:
tick
```
Leave the rest to default and try connecting! Connection established?

### Subscribe
Subscribe to topic:
```
/tt/training/chatroom/#
```

### Publish
Publish to topic:
```
/tt/training/chatroom/<YOURNAME>
```

## So what did we do?

Here is a [website](http://jwt.io) to see contents of the token you used.