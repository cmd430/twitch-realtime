# Twitch-Realtime 

Twitch realtime is a little library to interact with twitch's PubSub-Realtime Api.

You can install it with

```npm install --save twitch-realtime```

You can listen on the following topics:

|Topic|Description|Constant|Requires Token|
|---|---|---|---|
|Videoplayback|get updates about stream status and viewcounts|Realtime.TOPICS.VIDEOPLAYBACK|No|
|Bits|get updates about the Bits on the chat|Realtime.TOPICS.BITS|Yes|
|Whispers|Get incoming whispers|Realtime.TOPICS.WHISPERS|Yes|
