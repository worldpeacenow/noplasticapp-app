# Environment Configuration

Set env vars:

    firebase functions:config:set jwt.secret="123" jwt.ttl=3600
    firebase functions:config:set prismic.webhook.secret="123"
    firebase functions:config:set sheets.key="THE API KEY"

To set up local for use with env vars:

    firebase functions:config:get > .runtimeconfig.json
    
    
    
