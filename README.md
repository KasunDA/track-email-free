# track-email-free

Track email with Gmail and Google Analytics

# Process

1. The idea is to send a link similar to this:

```
http://www.google-analytics.com/collect?v=1&tid=UA-12345678-1&cid=CLIENT_ID_NUMBER&t=event&ec=email&ea=open&el=recipient_id&cs=newsletter&cm=email&cn=Campaign_Name
```

Inside the email, this link correspond to an invisible image Google Analytics uses to track emails.

2. You need to change several things on this URL:

```
http://www.google-analytics.com/collect?v=1&tid=__change_this__&cid=CLIENT_ID_NUMBER&t=event&ec=email&ea=open&el=__change_this__&cs=newsletter&cm=email&cn=Campaign_Name
```


